# Grid

### Mobile structure

### Desktop structure

#### Screen setup
When creating a desktop view, use the minimum size of 1440 * 850px. Height should match the content it needs to fit as long as it’s at least 850px.
For views shorter than 850px, align them the way they would be implemented. If you’re creating a view larger than the width of 1440px (i.e. fluid sidebar with layout - see subsection “Allowed variations”), go above the minimum width to fit the content.

#### Mockup layout
Use the standard layout size for both static and responsive screens to keep all design files consistent.

Total width: 1060px
Columns: 8 * 80px
Gutters: 60px

#### Navigation
The product top- and bottom navigations are responsive to the full viewport and don’t follow the layout width constraint.

#### Allowed layout variations
Use one of the following layouts to set up your view’s content.

#### Not allowed layouts
DO NOT use one of the following approaches when setting up your content.

### Desktop content

#### Content alignment
Content can be added in two ways:
1. Straight on background - content matches the full width of the columns.
2. As blocks - content is padded inside a container (referred to as "block").

#### Paddings & internal columns
Blocks added on the layout have an edge padding of 15px. All columns added inside the blocks have their individual 15px side padding, making the total padding between two columns 30px. For tables, this system is already implemented inside the table symbols. 

**Examples of blocks with internal columns**
