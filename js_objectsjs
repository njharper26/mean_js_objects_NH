// Challenge #1

// let students = [
//     {name: 'Remy', cohort: 'Jan'},
//     {name: 'Genevieve', cohort: 'March'},
//     {name: 'Chuck', cohort: 'Jan'},
//     {name: 'Osmund', cohort: 'June'},
//     {name: 'Nikki', cohort: 'June'},
//     {name: 'Boris', cohort: 'June'}
// ];

// for (let i = 0; i < students.length; i++){
//     let x = students[i].name;
//     let y = students[i].cohort;
//     console.log("Name:", x, " Cohort:", y);
// }

// Challenge #2

let users = {
    employees: [
        {'first_name':  'Miguel', 'last_name' : 'Jones'},
        {'first_name' : 'Ernie', 'last_name' : 'Bertson'},
        {'first_name' : 'Nora', 'last_name' : 'Lu'},
        {'first_name' : 'Sally', 'last_name' : 'Barkyoumb'}
    ],
    managers: [
       {'first_name' : 'Lillian', 'last_name' : 'Chambers'},
       {'first_name' : 'Gordon', 'last_name' : 'Poe'}
    ]
 };

for (let type in users){
    console.log(type.toUpperCase());
    let str = '';
    for (let i = 0; i < users[type].length; i++){
        len = users[type][i].last_name.length + users[type][i].first_name.length;
        str = i + 1 + " - " + users[type][i].last_name + ", " + users[type][i].first_name + " - " + len;
        console.log(str);
    }
}
