# HTML & CSS

### Index.html

The `index.html` file is a foundational HTML document that provides a structured layout for a web page. Below is a breakdown of its contents:

#### HTML Structure

- **DOCTYPE Declaration**: Specifies the document type and version of HTML (HTML5).
- **html Tag**: The root element of the document with `lang="en"` attribute, indicating the language is English.
- **head Section**:
  - **meta charset**: Defines the character encoding (UTF-8).
  - **link**: References the stylesheet `styles.css`.
  - **title**: The title of the page, "The Basic Language of the Web: HTML".
- **body Section**:
  - **div.container**: A wrapper for the main content.
  - **header.main-header**: Contains the site title and navigation links.
  - **article**: The main content area with a nested header and multiple paragraphs and images.
  - **aside**: Contains related posts with images and links.
  - **footer**: Includes copyright information.
  - **button**: A like button with a heart icon.

#### Content Highlights

- **Header**: "The Code Magazine" with navigation links to Blog, Challenges, Flexbox, and CSS Grid.
- **Article**:
  - **Title**: "The Basic Language of the Web: HTML".
  - **Author Info**: Posted by Laura Jones with a date.
  - **Main Content**: Explains what HTML is, its importance, and why one should learn it.
- **Aside**: Lists related posts with thumbnails and authors.
- **Footer**: Contains copyright information.

### Styles.css

The `styles.css` file provides the styling rules for the HTML elements defined in `index.html`. Here is a breakdown of the styling applied to each HTML tag:

#### General Styles

- **Global Selector (\*)**: Sets margin and padding to 0 for all elements.
- **body**: Defines the text color, font, top border, and positioning.
- **nav**: Sets the font size for navigation links.
- **article**: Adds bottom margin to the article.

#### Heading Styles

- **h1, h2, h3**: Applies a color (#1098ad) to headings.
- **h1**: Sets font size, text transformation, and style.
- **h2**: Sets font size, relative positioning, and an after pseudo-element.
- **h3**: Sets font size and margins.
- **h4**: Sets font size, text transformation, and alignment.

#### Paragraph and List Styles

- **p**: Defines font size, line height, and bottom margin.
- **ul, ol**: Adds left margin and bottom margin to lists.
- **li**: Defines font size and bottom margin for list items.

#### Specific Element Styles

- **h1::first-letter**: Removes italic style from the first letter.
- **h3 + p::first-line**: Custom styling for the first line of paragraphs following h3.
- **#author**: Styles the author paragraph with italics and a specific font size.
- **#copyright**: Defines font size for the copyright text.
- **.related-author**: Styles related post authors with font size and weight.
- **.related**: Removes list styling from the related posts list.
- **.container**: Sets the width and centers the content.
- **.main-header**: Defines the background color, padding, margin, and height for the header.
- **.post-header**: Adds bottom margin to the post header.
- **aside**: Sets background color, borders, padding, and width.
- **li:first-child**: Bold styling for the first list item.
- **li:last-child**: Italic styling and removes bottom margin from the last list item.
- **article p:last-child**: Red color for the last paragraph in articles.
- **a**: Styles for different link states (link, visited, hover, active).
- **.post-img**: Makes post images responsive.
- **nav a:link**: Adds margin and inline-block display to navigation links.
- **button**: Styles the like button with font size, padding, cursor, and positioning.
