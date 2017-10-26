# Alexa-Skills-normal-quiz-game

Intent Schema:
{
  "intents": [
    {
      "slots": [
        {
          "name": "QNumber",
          "type": "Q_Num"
        }
      ],
      "intent": "QuizIntent"
    },
    {
      "intent": "AMAZON.NextIntent"
    },
    {
      "intent": "AMAZON.HelpIntent"
    }
  ]
}


Custom slot type:
Q_Num--0,1,2,3,4,5,6,7,8,9,10

Sample utterances:
QuizIntent please ask me question {QNumber}
QuizIntent Please ask question {QNumber}

Start the skills
Alexa start unitedstatesquiz
