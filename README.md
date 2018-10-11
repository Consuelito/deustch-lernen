# deustch-lernen
to learn german, get prepared for your next job opportunity or any business presentation

classes: tutor, students, moderator, lessons
interactions: tutors post their availability. Students save the date. Moderator helps during the lessons.

var Tutor = {
name: 'tutor',
task: 'grammar help'
}

var Student = {
name: 'student',
task: 'to participate'
level: intermediate
}

var Moderator = {
name: 'Moderator',
task: 'intensify'
}

var Lessons ={
name: 'Lessons',
task: 'tongue trainning'
}


var Person = class {
constructor(name,level) {
this.name = name
this.level = level
}
    attend(meetup) {
        this.meetups.push(meetup)
        meetup.attendeese.push(this)
    }

}


var Meetup = class {
    constructor(name) {
        this.name = name
        this.attendeese = []
    }  
}



var Student = new Person('student','level')

console.log(Student)
