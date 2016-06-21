# June 20th, 2016

Today was a tough one. But I learned so much about structuring an object, I will probably practice this more as we go. But I found it very handy for handling variables and functions in relation to one need and it was easy to duplicate after getting the one problem correct.

I think that a lot of this data would probably fit-together better as a table, maybe that's a future project? (based on the reading...)

This whole thing blew my mind, today:

```javascript
june201.listStudents = function() {
  var studentList = document.getElementById('studentList')

  for (var i = 0; i < june201.students.length; i++) {
    console.log(june201.students[i]);
    var listItem = document.createElement('li');
    listItem.textContent = june201.students[i] + ' is Sam\'s favorite';
    studentList.appendChild(listItem);
  }
}
```
I bookmarked it so that I can continue to reference it.

  (come to thing of it, I'm actually understanding it more each time I see it!)
