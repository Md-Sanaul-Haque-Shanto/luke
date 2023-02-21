[Website](https://md-sanaul-haque-shanto.github.io/mquiz-app/index.html)

## Got a good quiz?

Submit a Pull Request, with your quiz added to the END of `quizzes/{category}.json` file. Make sure the quiz is in this format:

```
{
  "question": "Your question",
  "description": "A description is required only for multi-input type",
  "type": "checkbox / radio / input / multi-input",
  "choices": ["answer1", "answer2", "answer3"], - for radio and checkbox types
  "correctAnswer": "A single string for input type. A number for radio type. An array of numbers for checkbox type. An array of strings for multi-input type.",
  "madeBy": "your name / github nickname" - optional
}
```

### What you need to know

- There is 40 seconds time limit per question.
- Quiz answers are case insensitive.
- Quiz description is preformatted. You can use \n, \t, double spaces and etc. Double space is preferable for an indent because \t takes too much space.
- HTML markup is parsed as plain text.
- <in> wildcard represents an input for multi-input quizzes.
- Values in inputs are trimmed for text input type quizzes.
- There are no limits for the number of choices for radio and checkbox quiz types. However, let's keep this number reasonable. 
- Text input values cannot start with a whitespace.

Project Varsha:

Student:
acount creation :	Email-----  JWT Token Verification.
					Password--
Profile: School Name, Date of birth, Class[if class 10 then show gpa box, if grade hsc then show ssc gpa box with institute name and year,if uni then show hsc result,], Full address, Phone Number, profile image, live contest history, course history, practice history, student_blog, student_profile_id, student_id,contribution_point, profile_createdAt, profile_updatedAt, profile_username, profile_role[admin, student, blog_writter,course creator,quiz_creator], profile_ip,varsha_coins, profile_type[beginner,intermediate,advanced,premium].


student_blog:	blog_id, blog_title, blog_type, blog_authors, blog_details, blog_slug, blog_createdAt, blog_updatedAt 

student_blog_comments: blog_id, blog_reply, blog_reply_by,blog_replyAt, blog_reply_updatedAt.

Course panel:	course_id, course_slug, course_authors, course_for,Course_price,course_description, Course_details, course_modules, course_createdAt, course_updatedAt.

