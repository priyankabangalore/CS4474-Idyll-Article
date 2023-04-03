
[meta title:"Turkey Game" description:"Short description of your project" /]

[Header
  fullWidth:true
  title:"Turkey Cooking Simulator"
  subtitle:"Welcome to our Redesign of the Turkey Cooking Simulator"
  author:"Priyanka Bangalore (pbangalo), Anusha Sheikh (asheik55), Eileen Carette (ecarette), Erica Daiying Zhu (dzhu22), Evan Chambers (echamb9)"
  date:"Mar 29, 2023"
  background:"#222222"
  color:"#ffffff"
   /]


 [a href:'https://docs.google.com/presentation/d/16LVJfLk_cvI9AjFh7OyhxBHFGyEui16x6aA8a2MXa2E/edit?usp=sharing']Click Here[/a] to view our presentation

# Executive Summary

Turkey Cooking Simulator is a cooking game, developed by Scott Mobley, Robert J. Chen, Benjamin Kwok, and Sheen Kao depicted a classic American thanksgiving, and the cooking of its delicacy: turkey.

Our primary goals with the redesign of Turkey Cooking Simulator are to narrow the gulf of execution, making it more obvious to the user what steps they need to take to use the system and to provide a more user-friendly experience, by switching from a task-centric design to a user-centric design. We accomplished these goals in a variety of ways.

To narrow the gulf of execution, we provided the user with a clearer tutorial to help them develop a more accurate mental model of the game, which also increases the accessibility of the game. The tutorial will include information such as how the user can go to the store (by clicking on the flyer on the counter). In turn, this addresses the negative transfer of the original design and bridges the gulf of execution and evaluation. The tutorial uses progressive disclosure alongside chunking as the text and multimedia is divided into different screens and the user has the option to proceed to the next step or skip the tutorial entirely. Being able to progress through the tutorial or skip it entirely grants the user more control of their own experience. We have also given users more control by allowing them to choose their partners gender in the game.The tutorial icon (question mark icon) is available for a user to click on to review the information at any point during the game which improves visibility. This way, users can reduce the workload on their working memory as they do not need to memorize the information mentioned in the tutorial. 

We have also redesigned the game to ensure the userâ€™s perceived affordances match the actual affordances. We have added a blinking cursor to the user name textbox to improve affordances. We have also redesigned the store and used a metaphor for a shelf in a store to help users utilize a previous mental model surrounding shopping and purchasing ingredients. The redesigned store externalizes information using price tags to show prices, and displaying an item description on a clipboard when a user hovers over the item. This new redesign also improves visibility, allowing users to have a better view of what is available for purchase. We also ensured in our redesign that we provide users with feedback when they purchased an item in the store so the user has a clear understanding of the effect of their action. We have also included more constraints in our redesign, by eliminating non-purchasable items and only displayed items to users that they can buy (so long as they can afford them). By making this change, we are minimizing false affordances, as users can buy anything they click on in the store. Additionally, in the redesign of the store shelf, we have also incorporated Hickâ€™s law by categorizing items into different categories, thus minimizing the number of alternatives for each sub-section to make user decisions easier.

We have also captured potential false causality existing in the game and redesigned the dialogue to address it. We added a checkbox allowing users to select if they want the dialogue to be auto played. In the original design, it was difficult to determine if a userâ€™s clicking action in the game caused the dialogue to progress, or if it progressed on its own. Now, they are aware of what is causing the dialogue to proceed: their clicking action or the passing of time via auto play.
Likewise, we have also added a â€˜Startâ€™ button on the loading page of the game to indicate the game has finished loading to improve visibility, aiding users in understanding next potential actions.

To design from a user-centric perspective, we have made several quality-of-life changes that improve the user experience. For example, we have added a volume control button using a sound icon, so that the user has the option to reduce or eliminate the rather aggressive music at any point during the game. The addition of the rating system displayed at the end of the game will provide the user with feedback that will give them a sense of how well they performed. Likewise, a scoreboard of individual past attempts will be displayed at the end of each game, to provide the user with a performance comparison. We have also organized the help menu, and made the table of past actions in the â€œCooking for Dummiesâ€ easier to understand. In the redesign of the scoreboard and start page where we added gender options we used law of proximity and law of enclosed region from the Gestalt Laws to ensure the information looked structured and organized to the user.

For any new icons or buttons we added in our new design, we ensured we maintained internal consistency and external consistency, and used icons that are familiar to the users so there are no gulfs of execution and evaluation created due to our redesign.

These will also help users develop a clearer, more accurate mental model of the game. As well, we will replace the skeuomorphic design of the store with a simpler, flat-screen design that is easier to navigate.


[var name:"state" value:0 /]

[Scroller currentStep:state]

  [Graphic className:"d3-component-container"]
    [CustomD3Component className:"d3-component" state:`state+1` /]
  [/Graphic]

  [Step]

    ## Markup

    Idyll is based on Markdown.

    You can use familiar syntax
    to create **bold** (`**bold**` ) and *italic* (`*italic*` ) styles,

* lists
* of
* items,

    ```
    * lists
    * of
    * items,
    ```

1. and numbered
2. lists
3. of items,


    ```
    1. and numbered
    2. lists
    3. of items,
    ```

    in addition to [hyperlinks](https://idyll-lang.org) and images:

    ![quill](static/images/quill.svg)

    ```
    ![quill](static/images/quill.svg)
    ```
  [/Step]

  [Step]
    ## Components

    Components can be embedded using a bracket syntax:

    ```
    [Range /]
    ```

    and can contain nested content:

    ```
    [Equation]e = mc^{2}[/Equation]
    ```

    Components accept properties:

    ```
    [Range value:x min:0 max:1 /]
    ```

    that can be bound to variables to achieve interactivity (more in next section).


    A variety of components are included by default. See [all the available components](https://idyll-lang.org/docs/components/). You can also use any html tag, for example: `[div] A div! [/div]`.

    To create your own, add it to the `components/` folder. There are examples of how to use Idyll with React and D3 based components already included.

  [/Step]

  [Step]
    ## Interactivity

    Here is how you can instantiate a variable and bind it to a component:

    [var name:"exampleVar" value:5 /]

    [Range min:0 max:10 value:exampleVar /]
    [Display value:exampleVar /]

    ```
    [var name:"exampleVar" value:5 /]

    [Range min:0 max:10 value:exampleVar /]
    [Display value:exampleVar /]
    ```
  [/Step]

[/Scroller]

[Scroller]

  [Step]

    ##Scroller

    The `Scroller` component is used to create scroll-based presentations. It can be used to create scrollytelling articles similar to this.
    It takes a property `currentStep` which is updated when the user scrolls to a different step.

    A persistent graphic may also provided using the `Graphic` component in order to create visualizations.

  [/Step]

  [Step]

    ## Learn More

    To learn more see the documentation at [https://idyll-lang.org/docs/](https://idyll-lang.org/docs/),
    join our [chatroom](https://gitter.im/idyll-lang/Lobby), or see the project on [GitHub](https://github.com/idyll-lang/idyll).
  [hr /]

  [/Step]

[/Scroller]

[br/]
# Design Principles

## 1. Metaphor


## 2. Affordance
An affordance is defined as what a user can do, given their capabilities in the system. In the redesign of our game, a blinking cursor appears when inputting your name on the start game page, to indicate that you are typing. This was done to improve the affordance of the game as in the original design, when a user hovers their mouse over the text box or clicks on it to type, there is no visible cue that they are typing or can type in the box. Adding a cursor adds a dynamic affordance because although there are instructions present to indicate entering your name in the textbox, forward feedback in the form of a blinking cursor shows the user that the game is responding to the information it is receiving. Likewise, we have minimized false affordances in the redesign by only putting purchasable items in the store. In the original game, when users entered the store, they were shown a variety of items, some of which looked purchasable, but had no reaction once clicked. Hence, by removing items that a user cannot purchase, we are minimizing their false affordances, which suggests to users that they can commit an action they actually canâ€™t.

## 3. Visibility
An important visibility principle is making sure an object is distinguishable from the background, its status is clearly indicated, what actions can be performed on the object and what consequences would occur as a result of those actions. In the original inventory/grocery store setup screen of the game where the user would select what items to buy to cook the turkey with a set amount of money, the visibility of the items available to purchase was very poor. We redesigned the background of the screen from a grocery store with a circular shelf to a simple, linear shelf background free of any distractions from other products that canâ€™t be purchased. We also added a grocery list that kept track of what items had been bought. This redesign made it very clear what items were available to be purchased and presented them all in the same uniform line and size making it easier to see all of the potential options in one place instead of how it was positioned on the old background where some objects were not immediately noticeable. Another element we added in our redesign of the game to increase visibility is a â€˜Start Gameâ€™ button on the loading screen, to indicate that users can click on the button to play the game. In the original design, this button said â€˜Done!â€™, which wasnâ€™t visible enough in indicting what actions a user can perform, and the effect of the action.

## 4. Accessibility
Accessibility is defined as making a system inclusive to those who are often overseen when making applications. Making a simple game like the Turkey Cooking Simulator accessible requires making the instructions easy to understand and making sure the game is easy to navigate so it is an enjoyable experience for all users. Adding a tutorial that is accessible at any point during the game helps increase the accessibility of the game to various users who may require it. Written tutorials that the user can access at any point help by providing users with extra clarity and accommodating different learning styles. To increase inclusivity, in our redesign, we have added an opton for users to choose their partnerâ€™s gender, rather than having the system choose the userâ€™s partnerâ€™s gender based on their chosen gender. This makes the game more inclusive to all users.

## 5. Confirmation
Confirmation is a method of asking a user to ensure that their desired action is truly what they want to do. In the Turkey Cooking Simulator, completing the cooking of the turkey by taking it out of the oven is a critical and irrevocable action in the gameplay. By clicking the turkey, users are shown a confirmation popup as to whether or not they would like to remove the turkey from the oven to complete the game. Hence, it is important to make sure that this is what the user is intending to do when they click on the turkey in the oven. This is why we chose to maintain the original design that uses a confirmation popup when a user clicks on their turkey in the oven. This helps minimize user errors. 

## 6. Externalization of Information
It is important to maintain a good balance between what information is visible on the screen that the user needs to make a decision readily and what needs to be internalized to prevent overwhelming. In the original game, all the information in the grocery store pertaining to the productâ€™s prices and description was internalized so the user could only access it if they hovered over the product. We redesigned the grocery store information so the prices and categories the product belongs under are readily displayed on the screen instead of having to hover above the product to see it. This helps the user see important information quicker while also not cluttering the screen and overwhelming the user by keeping the descriptions internal unless needed. 

## 7. Constraints
Constraints are commonly used to limit a userâ€™s range of possible actions in a way that navigates them to a correct or doable action. In the previous design, users were shown various items in the store, some that could be purchased, and some that couldnâ€™t. In our redesign, we have eliminated non-purchasable items and only displayed items to users that they can buy (so long as they can afford them). By making this change, we are minimizing false affordances, as users can buy what they click on in the store. In the original version of the game, some of the items in the store looked purchasable but had no effect once they were clicked as they were not purchasable, inconveniencing a user and causing potential confusion.

## 8. Principle of familiarity
The principle of familiarity indicates that people have a preference for things that they are familiar with. This includes icons, buttons, and options within a game that are commonly used in our contexts. In the original game, this principle is used for items like a player's wallet, oven controls, or even products in the store. In our redesign, we are continuing to use this principle by implementing a volume control button using a sound icon. This is an icon that many users will find familiar due to its use in many other applications. A userâ€™s familiarity with the physical forms will activate their mental models when they see the icons, items, and buttons in the gameâ€™s UI. Hence, we added the volume button and kept the wallet and oven buttons.

## 9. Chunking
Chunking is used to break apart text and multimedia to benefit short-term memory, and reduce strain on working memory. In the original design, chunking is depicted as the information in the help manual is divided with images, and into different pages of the help book to help users understand and process the information better. Hence, we chose to keep the existing design to maintain the chunking pattern.

## 10. Mapping
Mapping is related to control and its effect in a system. Users can commit an action, and expect a change in the interface to occur. Throughout the original and our redesigned game, all controls map to the corresponding output. Both versions avoid single controls for various functions, and let users know beforehand what controls commit what behaviour. In regards to mapping layout, while the keyboard and mouse are used for some controls and arenâ€™t dependent on the UI layout, in our redesign, we have implemented an auto play button displayed inside the dialogue boxes that pop up, for users to be able to automatically play the dialogue. Users know exactly what the option does, and how it maps (correlates) to the dialogue.

## 11. Fitt's Law
Fittsâ€™ law is a predictive model of human movement, proposed by Paul Morris Fitts. In layman's terms, the law states that â€œthe amount of time required for a person to move a pointer (e.g., mouse cursor) to a target area is a function of the distance to the target divided by the size of the target. Thus, the longer the distance and the smaller the target's size, the longer it takes.â€ In our redesign, we have deemed the original target sizes and distances from a user's pointer as small enough, minimizing how long it takes for a user to move their cursor to the target. Additionally, the original design has the gameplay occur in a window smaller than the screen used to view it, further minimizing the distance between the userâ€™s cursor and any target options. Hence, we are keeping the original design of target sizes, screen sizes, and target distances.

## 12. Semiotics
Semiotics is defined as â€œthe study of symbolic communicationâ€. This can be done using icons, indices, or symbols. By maintaining the gameâ€™s original icons for items like a userâ€™s wallet, store items, and oven controls, we are maintaining a level of familiarity between a digital item in the game and a physical item a user has experience with. This in turn uses semiotics, as the icons are used to represent something in a symbolic manner. To add to our use of semiotics - specifically icons - we are implementing a volume control button using a sound icon, giving users the ability to adjust or mute the background musicâ€™s volume. The sound icon is one that many users will find familiar due to its use in many other applications. 

## 13. Consistency
Consistency ensures that users do not have to learn new representations like icons or ways of doing things for tasks, by keeping them consistent within the system. The original game has some external consistency. For example, the help menu button is displayed with a question mark, which is widely used as the help menu icon in applications. Therefore, we chose to keep this design. In our redesign, we are adding a volume control feature, which will have a sound icon to represent it. This ensures external consistency as the sound icon is also used by many applicationsâ€™ volume control features.To maintain internal consistency, we are using the same font, colour, and style in the start game page, despite adding more options. Likewise, for the displayed oven temperature, we are adding unit F for Fahrenheit, keeping it consistent with the temperature shown in the cookbook, further reinforcing internal consistency.

## 14. Transfer
Transfer is the process in which past experiences affect the learning and performance in a new situation. Ideally, we would want the game to have a high transfer so the user can navigate the game easily using their existing conceptual models built from their experiences of playing other cooking games. This game has a high conceptual level transfer on a macro level. Usually, cooking games involve going to the store and purchasing ingredients, or adding ingredients to pots or pans. Our game uses the same concepts, which give users a positive transfer when navigating the game. However, the low task implementation on a micro level has a negative transfer. Games usually allow users to navigate to different locations by clicking on doors or using direction keys to move to the character. In this game, the flyer is the entry point to go to the store which could be misleading to the user since it looks like a prop, not a gateway to another scenario. To address this negative transfer, we included a brief tutorial at the beginning of the game which will inform users that by clicking on the store flyer, they can go to the store to purchase ingredients. The information that is not transferred from previous experience is given to the user via the tutorial so that they can navigate the game with ease.

## 15. Control
Control is defined as the amount of influence a user has over their interface of the system, and how to ensure nothing is being forced upon them. In the original game, the background music volume could not be controlled with no option to mute. Hence, if the user wanted to listen to other things, or even turn off the gameâ€™s sound without turning off their systemâ€™s sound they couldnâ€™t. In our redesign, we wanted to ensure that users are given control over their individual preferences. Therefore, we are adding a volume control function which gives users the option to change the volume level or mute the music. We will also include this function on all screens so that the user has control of the volume at any time during the gameplay. We also give users more control over the characterâ€™s preferred partner gender, as previously the original game only allowed users to choose their own gender, giving them the opposite gender as their significant other. In our redesign, users can choose their own gender, as well as the gender of their significant other, increasing the amount of control they have in the game. Lastly, we have increased a userâ€™s control in the game by adding a auto play option located within the dialogue popups at the bottom of the interface. This allows users to automatically progress through dialogues, creating a smoother experience.

## 16. Feedback
Feedback is often used in applications to inform a user of their action, or the effect it caused. We want to provide users with immediate feedback to inform them of what has been done. Since in our redesign, we have modified the store to better organize the items, we have ensured that when a user purchases an item in the store, the item and price tag will be removed from the shelf right away to inform the user that the item has been purchased successfully. This provides a user with indirect feedback, letting them know that the item was purchased and need not be repurchased. Likewise, the appropriate amount will be subtracted from the userâ€™s wallet to provide feedback to the user on their action, and let them know that their transaction was successful.

## 17. Causality
Causality is defined as an effect produced by user action, the cause. Throughout the game, there are dialogues that pop up at the bottom of the screen. In the original game, the dialogue can be clicked on to move to the next dialogue or will disappear from the screen if the current dialogue is over. Also, the dialogue automatically proceeds to the next one. However, since the game requires users to click on objects to interact, sometimes it is hard to know if the dialogue is changing due to the user's clicking actions, or if it is automatically changing. This leads to false causality of what is affecting the dialogue. Therefore, to eliminate false causality, we added a checkbox in our redesign of the dialogue which let users choose if they want the dialogue to be on autoplay or not. This made users aware that autoplay is an option, also if they chose to uncheck the autoplay action, then they know if the dialogue changes it is due to their clicking action.  

## 18. Hick's Law
Hicks law is a psychological principle developed by William Edmund Hick, that relates a peronâ€™s decision making time with the number of available choices. According to Hickâ€™s law, the time it takes to make a decision increases as the number of alternatives increases. Since this is a game, we would like to lighten the user's usage of their mental cognitive load, without overwhelming them with difficult decisions. Therefore, in our redesign of the store, all of the ingredients and tools needed to cook a turkey are divided into different categories, and each category has fewer options than the original game. This makes it easier for users to make purchase decisions as the number of alternatives has greatly decreased, and been categorized for further reduction.

## 19. Gestalt Law
According to the Gestalt laws, the law of common regions suggests that we perceive elements located in the same closed region as belonging to the same group. Therefore, in our redesign of the scoreboard shown at the end of the game, we have included the userâ€™s High Score, Average Scores and Past Scores together on a translucent brown textbox. This makes the scores appear to be grouped together. Thus, when users try to compare their scores with their average scores or past scores, it is easier to do so. The law of proximity under the Gestalt laws is used in our redesign through the addition of a checkbox for users to choose their partnerâ€™s gender. We arranged the start page containing this information so that the Player Gender and Partner Gender options are located close to each other and slightly farther away from the game mode option, so these 2 related elements (both about gender) are perceived to be grouped together by users. In turn, this makes the page appear more organized and structured.

## 20. Progressive Disclosure
Progressive disclosure is a design technique that prevents overwhelming a user by limiting the amount of information they receive at a given time. In our redesign, we used progressive disclosure in the tutorial displayed at the beginning of the game. Instead of providing users with a list of information all on one page, we designed the tutorial to have 3 screens, where each screen only provides information about one item to the user. Users are given the option to proceed to the next tutorial page or to skip the entire tutorial depending on if they are familiar with the game, or if they want to learn more. Using progress disclosure, users are less overwhelmed with information and can only see the information they are interested in, without seeing everything at once (which can be overwhelming).


# A Final Hueristic Evaluation of our System 

## 1. Visibility of System Status 
The first heuristic is the visibility of the systemâ€™s status, defined as â€œkeeping users informed about their actions and whatâ€™s happening at a given interactionâ€. Our redesign utilizes this heuristic by maintaining the previous confirmations that inform a user that the turkey might require more time in the oven and a confirmation that asks a user if they are sure they would like to remove their turkey from the oven and finish the game. This allows a user to stay informed of what is happening during the game, and their status upon completion of the game.

## 2. Match Between the System and the Real World
The second heuristic is creating a match between the system and the real world, defined as â€œ a system should always speak the userâ€™s language and follow real-world conventionsâ€. In the original design, this was strongly utilized, as the oven controls and store closely resembled that of a real oven and store, respectively. In our redesign, we further utilize this heuristic by adding a unit of temperature to the oven, making all items in the store purchasable, and having prices below all items for users to plan their purchases. By adding features to make the Turkey Cooking Simulatorâ€™s interface match the real world, users will find it easier to navigate the system and play the game.

## 3. User Control and Freedom
The third heuristic is user control and freedom, defined as â€œdesign should never impose an action on the user or make decisions for them. Instead, the system should only suggest which paths the users can take.â€ Our redesign utilizes this heuristic by maintaining the original gameplay that gives users the freedom to buy whatever they want from the store, set any temperature and time (even against the recommended temperature and time noted in the help manual), and remove the turkey from the oven at any time, with only a warning to let them know that the turkey might require more time. Our redesign also includes a method for users to reduce/mute the music that plays during the gameplay. This gives users more freedom in terms of settings and does not force a preset volume level on them. Users have complete freedom in the game, as the game is intended to mimic classic American thanksgiving with all the trials and tribulations associated. Users can even keep the turkey in the oven for as long as they want (or until it blows up the house!).

## 4. Consistency and Standards
The fourth heuristic is consistency and standards, defined as maintaining the level of the systemâ€™s internal consistency and external consistency. Internal consistency means the same design is used everywhere inside the system, and external consistency means the system uses established industry design conventions throughout. This game has good internal consistency and external consistency regarding its graphical design and cause and effect.
For internal consistency in graphic design, all clickable buttons in this game have the same wooden button design, and all dialogues have the same design. For our redesign of the start page where we added options for user character and partner gender, we have also used the original fonts and color used in the game to maintain internal consistency. The icons such as the help menu have a question mark which is a convention used for many applications. For our redesign, we added a volume button which has a sound icon which is also conventionally used to represent volume control features in many applications, thus maintaining external consistency.
For internal consistency for cause and effect, the same action will always lead to the same result, such as when the user drags on the closed oven door, it will be opened, or when the user clicks on the flyer they will be navigated to the store. For external consistency, when user click on an unchecked box, it means the option is selected, and it can be unchecked by clicking on it again, this is also conventionally used by many systems to allow user selection.

## 5. Error Prevention
The fifth heuristic is error prevention, defined as the system has the ability to capture user error and is designed to minimize user error. In this game we have implemented several features to ensure good error prevention. In our redesign of the store in the game where users can purchase ingredients, we made sure the items are placed with enough space between them so users do not click on the wrong item by mistake. We have also kept the original alert feature in the game where when the user attempts to take the turkey out of the oven and end the game, a message will be shown to the user confirming if s/he wants to end the game and the user has to click a button to confirm his/her action. This can avoid users ending the game by mistake and causing frustration. Additionally, the game only requires that the user only buy one turkey. In our redesign, after a turkey is purchased, all other turkeys on the shelf will be grayed out and become unselectable so a user knows they cannot purchase another turkey, preventing an error of purchasing more than 1.

## 6. Recognition vs. Recall in User Interfaces
The sixth heuristic is recognition vs recall in user interfaces, defined as the systemâ€™s design should promote recognition over recall to minimize usersâ€™ memory load. The system has no hidden menu and all buttons are clearly visible to the users to eliminate the need for users to recall. We kept the help menu feature from the original design and only reorganized its content to make it easier to read so users do not need to memorize all details of the game. This help feature is available throughout the game via clicking on the question mark button on the top right corner and this visibility allows users to recognize where to get help instead of needing to memorize.
We have also added a tutorial which is displayed at the beginning of the game, so users can learn about the basic features of the game that they need to know in order to navigate the game. This also allows return users to refresh their memory so they do not need to recall how to navigate the game. The users have the option to skip the tutorial if they feel they do not need this refresher.
The game also has a dummy cookbook item available for purchase which can record all cooking actions users performed so they can keep track of their activities and check their progress instead of needing to memorize their past actions.
In the original design, the user needed to click on the turkey when the game loaded to 100% to start the game, however, this might not seem obvious to the user that they need to click on the turkey to start the game. So, to eliminate this need to recall how to start the game, we added a start button on top of the turkey which will appear once the game finished loading to remind user that they can now click here to start the game.
Also, the game provided dialogue which gives users hints such as they need to go to the store to buy turkey first so users do not need to recall what tasks they need to complete to proceed with the game.
We have also modified the scoreboard shown at the end of the game to display past highest score and average score so users do not need to remember their past scores in order to do the comparison and evaluate their performance. This also promoted recognition over recall.
We have redesigned the store and displayed each itemâ€™s price via a price tag located below the item. When a user hover over the item, its description and functionality is displayed at the bottom left corner. The amount left in the userâ€™s wallet is also displayed at the bottom right corner. This allows users to simply recognize what each item is, how much they are, and what they can afford to buy, instead of needing to keep track of all this information in their cognitive workload. 

## 7. Flexibility and Efficiency of Use
The seventh heuristic is flexibility and efficiency of use, defined as a systemâ€™s flexibility in giving users various ways to complete the same task, benefiting new and expert users. Our redesign has increased the flexibility of the game by incorporating additional methods that are more efficient to use for repetitive tasks. In the game, there is lots of dialogue displayed at the bottom of the interface. The user can choose to press the autoplay button to progress through the dialogue faster if they feel that it is distracting them from their task. Alternatively, users can click on each dialogue to progress. Both methods perform the same function. Likewise, users can open the oven 2 different ways: by either clicking on the oven handle and dragging it down, or by double clicking on the handle.

## 8. Aesthetic and Minimalist Design
The eighth heuristic is an aesthetic and minimalist design, defined as maintaining a high signal-to-noise ratio in the graphics of a system. Our redesign of the grocery store layout is a good example of a high signal-to-noise ratio. Before our redesign, the grocery store was full of â€œnoiseâ€, as the background was distracting with many different products and objects that the user couldnâ€™t buy or even click on. When we redesigned the grocery store, we eliminated the grocery store background with a minimalist shelf background instead. The shelf still conveys the fact that the user is in a grocery store, but it removes all the distractions of all the items in the background that serve no purpose other than to distract users from their actual task of picking out their inventory. 

##9. Help Users Recognize, Diagnose and Recover from Errors
The ninth heuristic is helping users recognize, diagnose and recover from errors, which is defined as clearly informing users if an error has occurred, what the issue causing the error is, and how to solve it. In the original game, when users try to purchase something in the store that surpasses their remaining budget, a dialogue pops up at the bottom of the interface, informing the user that they cannot inform the item. Additionally, if a user tries to purchase a second turkey in the store, despite being able to afford it, a dialogue pops up at the bottom of the interface, letting the user know that they can only purchase 1 turkey for the purpose of the game. Likewise, if a user tries to prematurely take their turkey out of the oven (which ends the game), a popup is displayed that informs a user that the turkey might need some more time before serving. Hence, in our redesigned game, we have chosen to keep these original designs.

## 10. Help & Documentation
The tenth heuristic is help and documentation, defined as providing users with the help they need in an effective, task-oriented manner. Our game redesign involves incorporating a brief tutorial at the beginning of the game that lets the user orient themselves with common controls and also points to where the help button is. The redesign makes it easy to ask for help because the help manual is available at any point during the game and the first thing the tutorial explains is where to find the help manual in case the user needs it. The help manual and tutorial are focused on the userâ€™s task because they offer guidance on where to find specific control options and help the user orient themselves with their surroundings while still not taking away from the gameplay aspect of it. The help manual that users have available to them at any time during the gameplay provides users with a list of concrete steps they can carry out, about a specific part of the game. For instance, one section of the help manual pertains specifically to the oven and what can be done with the oven door, handle, and buttons.


# Recommendations for how the System can be improved in light of our Final Evaluation
In light of our final evaluation, while our redesign of the Turkey Cooking Simulator system makes it more user-friendly, utilizing many of the human-computer interaction principles we have learned, we recognize that it can be improved.

Firstly, the system could be improved by including a small shopping cart or bag that users can click on to see their potential purchases. Users can them remove items from their cart or bag, just like they can in any physical store. Not only does this minimize user error in the case a user accidentally purchases an item, but this also utilizes the third heuristic of user control and freedom. By including a shopping cart or bag in the store, users would have complete control over the items they are buying, without being forced to purchase something they didnâ€™t intend to buy. This would in turn increase familiarity, as in the physical world, we are able to add things to our shopping cart or online cart, with the ability to remove items before purchasing. 

Another way the system could be improved is by implementing a more modern, flat design, relating to the eighth heuristic of aesthetic design and minimalism.The current design and colourway of the Turkey Cooking Simulator is meant to mimic a classic American thanksgiving, hence the more retro/southern font and styles, and fall colours. However, if we were to reintroduce the game as a modern take on an American thanksgiving, using softer colours, calmer fonts, and flat graphics would promote an aesthetic and minimalist design. 

Additionally, the system could be improved by alerting users that they must enter their name to begin the game, as currently, the system allows users to leave the name textbox blank. This relates to the ninth heuristic of helping users recognize, diagnose and recover from errors. In a future design, users can be alerted of their error (not entering their name), and how to mitigate the error, by letting them know they must enter their name to continue the game.

Lastly, the system could be improved by giving users the opportunity to manually stuff, decorate, and put the turkey in the oven, rather than the system automatically doing all preparations for them Currently, the purchased items are placed on the kitchen counter, and glow when hovered over. This indicates to a user that clicking on the items will perform an action. However, this is not the case. By giving the purchased items a purpose to users, this would utilize the second heuristic of match between the system and the real world, as users would conduct preparations and cook in the game, similar to how they would in the real world, making the process more intuitive and increasing the challenge level. This improvement would also utilize the third heuristic of user control and freedom, as users would have more freedom in preparing and cooking the turkey, without actions being handled solely by the system.

In essence, while the changes our group made to the Turkey Cooking Simulator made the game more user-friendly, with clearer controls, navigation, and an objective, there is always room for improvement.
