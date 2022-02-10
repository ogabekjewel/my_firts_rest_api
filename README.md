# my_firts_rest_api
endpoints:
GET https://online-course-api.herokuapp.com/api/courses => get all course list

GET https://online-course-api.herokuapp.com/api/course/:slug => get specific course

PATCH https://online-course-api.herokuapp.com/api/course/:slug => update specific course vie course_id. form data example: { "course_author": "Some new name", "course_price": "new price", "course_duration": "new course duration", "students_enrolled": 5010, "keywords": [ "new", "keywords", "here" ] } !!! course_id cannot be changed !!!

DELETE https://online-course-api.herokuapp.com/api/course/:slug => delete specific course

POST https://online-course-api.herokuapp.com/api/course => create a new course. Form data example: { "course_name": "Complete React course zero to hero", "course_author": "Andea Negoe", "course_price": "100$", "course_duration": "5 hours", "students_enrolled": 5010, "keywords": [ "react", "javaScript", "jQuery", "bootstrap", "css", "html", "bootcamp", "zero to hero" ] } !!! course_id is auto-generated !!!
