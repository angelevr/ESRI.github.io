CSS = Cascading Style Sheets
Purpose is separation of content from presentation.
CSS is composed of RULE that act on SELECTORS

#### CSS - Selectors and Rules
- Tags
- Classes
- ID - #
- Pseudo Classes
    - :visited
    - :hover

### CSS - Where it Lives
- Inline: ```<h1 style="color:#000;background-color:#FFF">Title</h1>```
- Internal: ```<style>
            
            h2 {color:#FFF
                background-color:#000;
                }
            
            </style>```
- External: ```<lik rel="stylesheet" type="txt/css"href="master_style.css">


### CSS - Resedence
- Specifity takes precedence over generality
- id>class>tag
- inline>internal>external

![2022-04-21](https://user-images.githubusercontent.com/60888123/164498441-c311366b-10b7-4bce-a5d9-c163a5c1897a.png)
![2022-04-21 (1)](https://user-images.githubusercontent.com/60888123/164498447-1b8c91fc-944c-426b-85c5-5311732d6339.png)

### CSS - Pseudo-Selectors
- Links
  = a:link {color:blue}
  a:visited {color:purple}
  a:active {color:black}
- Hover
  - a:hover {background-color:blue; color:white;}
- Forms
  - input:focus {background-color:yellow}
  - input:valid {background-color:red}
  - input:required {background-color:lightgreen} 
- Children
  - li:firstchild {font-weight:bold}
  - ul .multi-list {color:yellow}
  - ul .multi-list>li {color:red}
  - ul .multilist>li>ul>li {color:blue}
  - ul .multilist>li>ul>li>ul>li {color:green}

### CSS - Primary Uses
Style
- Font
- Color
- Size
- Borders

Formatting
- Indents
- Margin
- Alignment
- Spacing

Layout
- Relative
- Absolute
- Float

Animation
- Hover and focus pseudo:selectors
- Turn content on and off, change its position, or change styles on the fly (with javascript)

**Beyond CSS**
LESS and SASS
- Use variables in CSS
- Use conditional statements

Compile to CSS

QUIZ
1. A pseudo-selector is used to select elements based on their: state
2. Where would you find internal CSS? between style tags within the web document
3. Which type of CSS has the highest precendece? inline
4. Which type of CSS tag has the lowest precendce? tag
5. The :active pseudo-selector applies when: the user is clicking on a link
