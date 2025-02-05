# 3-Column Preview Card

This project is a responsive 3-column preview card layout.

## Technologies Used

-HTML
-CSS

# Responsive Web Design

The project uses CSS Grid to create a responsive layout that adapts to different screen sizes. The layout changes from a 3-column design on larger screens to a single-column design on smaller screens.

### Media Queries

The following media query is used to adjust the layout for smaller screens:

```css
@media only screen and (max-width: 768px) {
  .wrap{
      grid-template-columns: 1fr;
  }
}
