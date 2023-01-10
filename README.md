# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
1.first we have to create assignment folder. In that create timetable folder.

2.inside the timetable folder create myproj folder.

3.create a simple table using table tag .In that,type your own timetable which is available in your CAMU.
### STEP 2
Add header row using th tag.we have to use body tag and write the html code in it.
### STEP 3
Add your timetable in the index.html.
### STEP 4
Execute the program

# CODE
```python
<!DOCTYPE html>
<html lang="en">
    <body>
        <img src="logo.png" height="150" width="1850" alt="LOGO">
        <table border="2" cellspacing="2"
        bordercolor="black"
        bgcolor="white" align="center">
        <tr>
            <th colspan="8">TIME TABLE</th>
        </tr> 
        <tr>   
            <th colospan=2>Reference Number:</th>
            <th colospan=2>22008608</th> 
            <th colospan=2>Name:</th>
            <th colospan=2>Balureddy Velayudham Gowtham</th>
        </tr>
        <tr>
            <th>DAYS</th>
            <th>I</th>
            <th>II</th>
            <th>III</th>
            <th>IV</th>
            <th rowspan="8">lunch break</th>
            <th>V</th>
            <th>VI</th>
            <th>VII</th>
            <th>VIII</th>
        </tr>
            <tr>
            <td>MONDAY</td>
            <td>Break</td>
            <td>19EY201/Rajesh Immanuel</td>
            <td>19EY201/Rajesh Immanuel</td>
            <td>Break</td>
            <td>CPM06/Jeevitha Subramani</td>
            <td>CPM06/Jeevitha Subramani</td>
            <td>Break</td>
            <td>Break</td>
        </tr>
        <tr>
            <td>TUESDAY</td>
            <td>19AI414/Gowri Ganesh</td>
            <td>19AI414/Gowri Ganesh</td>
            <td>Break</td>
            <td>Break</td>
            <td>19MA201/Parvathi S</td>
            <td>19MA201/Parvathi S</td>
            <td>19CS301P1/Shanmuga Priya S</td>
            <td>19CS301P1/Shanmuga Priya S</td>
        </tr>
        <tr>
            <td>WEDNESDAY</td>
            <td>19PH205/Suresh S</td>
            <td>19PH205/Suresh S</td>
            <td>19CY205/Thirumavalavan M</td>
            <td>19CY205/Thirumavalavan M</td>
            <td>Break</td>
            <td>Break</td>
            <td>19CS301P1/Shanmuga Priya S</td>
            <td>19CS301P1/Shanmuga Priya S</td>
        </tr>
        <tr>
            <td>THURSHDAY</td>
            <td>19EN101/Premraj R</td>
            <td>19EN101/Premraj R</td>
            <td>19AI414/Gowri Ganesh</td>
            <td>19AI414/Gowri Ganesh</td>
            <td>CPM06/Jeevitha Subramani</td>
            <td>CPM06/Jeevitha Subramani</td>
            <td>19PH205/Suresh S</td>
            <td>19PH205/Suresh S</td>
        </tr>
        <tr>
            <td>FRIDAY</td>
            <td>19AI414/Gowri Ganesh</td>
            <td>19AI414/Gowri Ganesh</td>
            <td>19EN101/Premraj R</td>
            <td>19EN101/Premraj R</td>
            <td>19MA201/Parvathi S</td>
            <td>19MA201/Parvathi S</td>
            <td>19CY205/Thirumavalavan M</td>
            <td>19CY205/Thirumavalavan M</td>
        </tr>
    </body>
</html>
```

# OUPUT

![TimeTable](image/SECTimeTable.png)


