# frontend-react-form1

### Exercise 1: Basic Form
Create a new component called `PersonStats`. In `PersonStats`, create a form that will allow the user to input their name, age, and how they feel right now. Once submitted, display the message: "Hello [NAME]. Your age is [AGE] and you're feeling [FEELING] below the text fields. It should use JSX to style the message.

### Exercise 2: Form that lifts state
- Create a `AppContainer` component to maintain shared state (an array of blog posts)
- Create a `HeaderComponent` that displays a `H1` header that says `My Blog`
- Create a `FooterComponent` that displays `This site created by [YOURNAME]`
- Create a `PostList` component that will be used to display a blog entry
- Create a `BlogPost` component that contains a form and allows you to enter a `blogTitle` and a `blogPost`
  - This should be a *controlled component* meaning all values come from and are saved to the component state
  - When the form is submitted, update the shared state which then should update your blog posts in state and then iterate the array creating a new `BlogPost` component for each blog post in the shared state array
  
  
