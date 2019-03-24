HANC
have a nice choose

frontend:
angular

backend:
nodejs
postgreSQL
GraphQL

功能：
註冊/登入
查課/排課
 課程篩選(teacher, courseName, session, require, courseId, unit, academy, departId, grade)
 自訂顯示課程/老師
 備案自訂
 隨機塞課
 同學推薦
 
API:


DB:

Base
 id
 create_at
 update_at

userLogin
 userID
 passwd
 
userProfile
 email

userCourseData
 userID
 classID
 priority (-1=disable)

userRecommend
 userID
 classID
 reason

classroomTime
 classID
 weekday
 session
 isTA
 classroom
 
couseData
 classNo
 couseID
 departID
 subjectID
 grade
 term
 class
 require
 unit
 className
 teacher
 hasTA
 sets
 limit
 comment
 academicYear
 semester