# Temporobo

A robot that logs your work according your activities everyday for  JIRA.
You are free to extend it to adapt to your scenario.

It is very useful when your manager asks you to log your work every day and you
forget how much time did you spend on each ticket.

# Get Started

It requires Python > 3.8

Work as daemon:
```
pip3.8 install -r requirement.txt
python3.8 robo.py -u <login>
```

or, log for specific date:

```
python3.8 temporobo.py -u <login> -d year-month-date
```
