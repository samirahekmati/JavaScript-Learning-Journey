# JavaScript-Learning-Journey
/*
Alex, Sara and Nancy are in the same class.
In math class, Alex's grades are 90, 80,95.
Sara's grades are 89,76,98
Nancy's grades are42,98,83
1.Calculate the average score for each student, then save that value
into a variable.
2. Find the highest average and then console log the student who has
the highest average
3.Averages may be the same.
*/

const alexGrade = (90 + 80 + 98) / 3 ;
const saraGrade = (89 + 76 + 98) / 3;
const nancyGrade = (42 + 98 + 83) / 3;

console.log('Alex average grade', alexGrade);
console.log('Sara average grade', saraGrade);
console.log('Nancy average grade', nancyGrade);

if (alexGrade > saraGrade && alexGrade > nancyGrade) {
   console.log('Alex has the highest average', alexGrade);
} else if(saraGrade > alexGrade && saraGrade > nancyGrade) {
   console.log('Sara has the highest average', saraGrade);
} else if (nancyGrade > saraGrade && nancyGrade > alexGrade) {
   console.log('Nancy has the highest average', nancyGrade);
} else {
   console.log('every body has the same average');
}
