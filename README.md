# Machine Learning Engineer Test

## Objective

- Make an intent classifier with the dataset provided in the repository in which the imput will be a phrase and the model must correctly classify it in one of the intentions defined in the dataset
- The main objective of the test is to assess the candidate's ability to solve problems and demonstrate his attempts, hypotheses, solutions clearly and the ability to analyze data, extract information, suggest conclusions, and support decision-making.

### Example interaction with the resulting model
Just a demonstrative example to understand the problem, the output can be formatted according to the candidate's preference so that it shows the intention and the confidence that the model returned
```
example 1:
input: como ocorre a transferência de processos para o SEI?
output: 
intent: processos_administrativos 
confidence: 96.7%

example 2:
input: quais são os documentos disponíveis?
output: 
intent: documentação
confidence: 83.2%
```

## Information about the datasets

The dataset is in the dataset.txt file in the repository, it is in the format:

```
## intent:intent_name1
- sentence1
- sentence2
...
- sentenceN

## intent:intent_name2
- sentence1
- sentence2
...
- sentenceN

...
```

## Instructions
- Clone this repository to your local machine
- Create a new github_repository
- Update your clonned remote url to your new github_repository using 
```
git remote set-url origin https://github.com/username/new_github_repository.git
```
- Make your repository private
- Give access to the user "lucasraggi89" and "lucasagra" in your repository
- Put all the code, logic, hypotheses, etc. organized in the nlp_test.pynb jupyter notebook of the repository (i.e. specific actions you would take based on your analysis) and methodology.

- Only commits before the deadline will be considered
- The deadline is in the 23:59 7 days from when you received this test

Tip: it is interesting to put your different approaches and attempts in the notebook to support decision making<br/>
Have fun!
