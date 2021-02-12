# Signature-Fraud-Detection

## Description

The SMS Ham-Spam detection dataset is a set of SMS tagged messages that have been collected for SMS Spam research. It contains a set of 5,574 SMS messages in English, considering both train and test data. The tagging standard was defined as `ham` (legitimate) or `spam`. 

The `train` and `test` files are formatted using the standard of one message per line. Each line is composed by two columns: one with label (`ham` or `spam`) and other with the raw text. Here are some examples:

```
ham   What you doing?how are you?
ham   Ok lar... Joking wif u oni...
ham   dun say so early hor... U c already then say...
ham   MY NO. IN LUTON 0125698789 RING ME IF UR AROUND! H*
ham   Siva is in hostel aha:-.
ham   Cos i was out shopping wif darren jus now n i called him 2 ask wat present he wan lor. Then he started guessing who i was wif n he finally guessed darren lor.
spam   FreeMsg: Txt: CALL to No: 86888 & claim your reward of 3 hours talk time to use from your phone now! ubscribe6GBP/ mnth inc 3hrs 16 stop?txtStop
spam   Sunshine Quiz! Win a super Sony DVD recorder if you canname the capital of Australia? Text MQUIZ to 82277. B
spam   URGENT! Your Mobile No 07808726822 was awarded a L2,000 Bonus Caller Prize on 02/09/03! This is our 2nd attempt to contact YOU! Call 0871-872-9758 BOX95QU
```

    Note: messages are not chronologically sorted.

For evaluation purposes, the `test` dataset does not prosent the categories (`ham`, `spam`). Therefore, the `train` data is the full source of information for this test.

## Objective

The goal of the this test is to achieve a model that can correctly manage the incoming messages on SMS format (`ham` or `spam`). Considering a real scenario, assume that a regular person does not want to see a `spam` message. However, they accepts if a normal message (`ham`) is sometimes allocated at the `spam` box.


## Run Solution

To run this solution please: 

1. Install the requirements.txt in python enviroment or not
2. Change the path_train variable to path to train dataset on your machine
3. Change the path_test variable to path to test dataset on your machine 
4. Open the Classify_Spam.ipynb file in jupyter notebook or vscode with python extension
