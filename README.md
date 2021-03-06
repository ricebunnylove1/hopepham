# Hope Pham Programming Portfolio

## Adventure Game :cat:
A game that I have been working on for my Intro to Programming class during the Summer of 2020 that featuers object-oriented programming principles inheritance, encapsulation, and polymorphism. [Adventure With KATS THE Pirate](https://github.com/ricebunnylove1/AdventureWithKATSThePirate)

### Image of Adventure Game Intro:

![Intro](https://user-images.githubusercontent.com/67672827/88486783-cbf8e180-cf45-11ea-83f1-6e130e6e3256.png)


## Programming Study Application :books: 
An application that enables to take a short quiz on programming terms and tries to receive points: [Programming Study App](https://github.com/ricebunnylove1/ProgrammingStudyApp)

### Image of Application Intro:

![ProgrammingStudyApp](https://user-images.githubusercontent.com/67672827/88249850-4803d880-cc6b-11ea-9425-fc70a082faf3.png)


## Explorable Areas :world_map:
An application enables the player to choose the places they want to explore and earn items for thier inventory: [Explorable Areas](https://github.com/ricebunnylove1/ExplorableAreas)

### Image of Explorable Areas App:

![ExplorableAreas](https://user-images.githubusercontent.com/67672827/88250495-61a61f80-cc6d-11ea-8387-f7a923efc6be.png)


## Underwater Zoo :octopus: 
An application allow player to learn about sea creatures and adopt one was well: [Underwater Zoo](https://github.com/ricebunnylove1/UnderwaterZoo)

## Adopt A Butterfly :butterfly:
An application that enables player to create their own butterfly: [Adopt A Butterfly](https://github.com/ricebunnylove1/AdoptAButterfly)

### Example of Adopt A Butterfly Player Class Code:

```markdown
 public class Player
    {
        public static string Name = "Anonymous Player";
        public static string Gender = "Anonymous Gender";

        public void Start()
        {
            BackgroundColor = System.ConsoleColor.White;
            ForegroundColor = System.ConsoleColor.Black;

            TextInfo TitleCase = new CultureInfo("en-US", false).TextInfo;
           
            WriteLine("Welcome to Adopt A Butterfly by Hope Pham. In this application, you will be able to adapt your very own butterfly. To get you started, please introduce yourself. What is your name?");

            Name = ReadLine();
            Name = TitleCase.ToTitleCase(Name);
            WriteLine("Hello " + Name +"!");
            ReadLine();

            WriteLine("Please include your pronoun.");

            Gender = ReadLine();
            WriteLine(Name + " like to be addressed as " + Gender + "." + " Now let's begin adopting your butterfly. Press enter to continue.");
            ReadLine();

            Clear();
        }
    }
```


## Shift Cipher :infinity: 
An application that encodes and decodes using a simple substitution cipher: [Shift Cipher](https://github.com/ricebunnylove1/ShiftCipher/tree/master)

## Strawberry Trivia Game :strawberry: 
This application allows the player to answers questions about strawberry and tries to receive points: [Strawberry Trivia Game](https://github.com/ricebunnylove1/StrawberryTriviaGame)

### Example of Strawberry Trivia Game Code:

```markdown
public class Game
    {
        public string Name = "Strawberry Trivia Game";
        public string Setting = "A classroom at Columbia";
        public int Goal = 10;

        public void Start()
        {
            Title = "The Strawberry Trivia Game by Hope Pham";
            WriteLine("Welcome to the Strawberry Trivia Game by Hope Pham. In this game you will learn fun facts about strawberry.             To get ready for the game there is a question you must answer first. What is your name?");
       
            Player.Name = ReadLine();
            WriteLine("Hello " + Player.Name + "! Let's play The Strawberry Trivia Game! Press enter to start!");
            ReadLine();
            
            Question strawberrySeeds = new Question();
            strawberrySeeds.QuestionText = "There are 200 seeds in a strawberry. Treu or false?";
            strawberrySeeds.CorrectAnswer = "true";
            Clear();

            Question strawberryGroupMember = new Question();
            strawberryGroupMember.QuestionText = "What is the flower family name that strawberry belongs to (that starts with the             letter r)?";
            strawberryGroupMember.CorrectAnswer = "rose";
            Clear();
        }
    }
```
