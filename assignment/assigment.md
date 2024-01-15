# SWE101: Programming Fundamentals

## Labs 02 CSS Fundamentals

### Task: Give Assignment 1 a makeover

We will be referencing the completed codebase of assignment 1 without non-completed challenged.

#### Body

1. Let's start off by setting the body display mode to Flex using `display: flex`. This will align all childrens of body in a Row.
2. However, we want it be stack in a column. We can change the flex direction by adding `flex-direction: column`.
3. This should appear as if we have done nothing, but the display mode is now flex. This enable us to tap on all the flexbox features. Let's add `align-items: center` to set all the childrens in the middle.

#### Title

1. The title is align to the left, let's put it in the middle. How can we do it?

#### Nav & Nav Link

1. The Nav bar looks too close. Let's spread them out evenly by using flexbox. Set the `nav` display mode to flex.
2. The default setting for flex direction is `row`. We can adjust the alignment of the childrens on the X axis using `justify-content`. Assign the value `space-between` to spread out the childrens without gaps at the end.
3. Great, the anchor link looks a little ugly with the underline and highlight. How can we remove the underline and change the color? Try googling the answer.
4. Let's add some hover effects, on hover, the text should change to the color blue. Try asking ChatGPT for the answer.
5. One final add-on, on hover, the color should change with a smooth transition. Find out how you can do that using ChatGPT.

#### Articles

1. Currently the title, img, and text are align in a column. Let's separate the title and article content and set the img and text side by side. To do this, let's first group the `img` and `p` by wrapping it within a `div`. Let's give the `div` a class of `article-contents` as we will be repeating it for all 3 articles.
2. In your css file, set that `div` to flex mode to align the children in a row.
3. Great! The `img` and `p` is too close, let's add a 4px gap the the `div`.
4. The articles are off-alignment. This is because the `p` tag is not restricted. Let's set a width limit to the `body`. Add a width of 600px to the `body`.
5. ...That doesn't seem right. Why do you think this is happening?
6. To fix it, create a new `div` just below `body` and should close just before the `body` closing tag.
7. Let's give that `div` and id of `body-container` and shift the 600px width from the `body` to this `div`.
8. The text are looks slightly off. This is because `p` and `ul` tag have a default margin-top & margin-bottom set to 16px. Let's set the margin of those 2 tags to 0.

#### Subscribe

1. The form `input` are to close. Let's wrap a `div` around the label and input for both email and weeklyUpdate.
2. Now wrap another `div` around those 2 `div` and give it an id of `input-containers`.
3. Let's set the `input-containers` to flex mode and give it a gap of 12px.
4. Next, set the form the flex mode, and add align the x-axis to `space-between` using `justify-content`.

#### Footer

1. Let's align the footer with the body width by setting the footer with a width of 600px as well.

#### Final Touch

We learn about how to work with `<hr />`. Try to add an `hr` tag between `header` and `main`, as well as `subscribe` and `footer`.

#### Challenge #1

The button looks rather boring. Give it a makeover and add in some hover animation. Play around with the border-radius, padding, and transition speed too.

#### Challenge #2

Clone the main page of the following website
1. https://www.google.com/
2. https://nodejs.org