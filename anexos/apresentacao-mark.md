Theme: notes
Palette: Red
Size: Wide

---
Layout: Title

# Tutorial 3
## Graphs & Diagrams


---
# Types of Graphs & Diagrams

There are 4 types of **Vizualizations**:

1. **Mind-Map** and **Org-Chart** are the simple ones. They draw a hierarchy of nodes. Their nodes can only contain text.
2. **Devices** (iPhone, iPad, Browser and MacBook) allow to put a frame around a content. This content can contain a subset of Markdown.
3. **Charts** (grid & sequence) are dynamic diagrams. They can have a variable number of "blocks". Like devices, each block can contain Markdown. 
4. **Graphs** (line-chart, spline-chart, area-chart, bar-chart, donut-chart, pie-chart) can be used to visualize series of data.


---
Layout: SectionTitle

# Mind-Map & Org-Chart

---
# Org chart

{{org-chart}}
Big Boss
	Boss 1
	Boss 2
		Employee



---
# Mind mapping
 

{{mind-map}}
Root Idea
	Child idea 1
		Sub idea child 1 
			sub sub idea 
		Sub Idea child 2
	Child Idea 2
		Sub Child idea
		Sub child idea 2
	child idea
	Another child idea



---
Layout: SectionTitle

# Graphs

---
# General Information

- We call a **series** a consistent set of data
- We call **data-point** a value of a series.
- Each series has a name and a set of value. 
- They are both separated by a colon :
- Each value is separated by a coma , Example : `Budget: 120, 130, 140` 

---
# Line Graph 

{{Line-Chart}}
- Serie 1: 1, 3, 4, 2
- Serie 2: 2, 1, 2, 4

---
# Spline Graph 

{{spline-chart}}
- Serie 1: 1, 3, 4, 3
- Serie 2: 2, 1, 2, 4


---
# Area Graph 

{{area-chart}}
- Serie 1: 1, 3, 4, 3
- Serie 2: 2, 1, 2, 4
---
# Bar Graph
{{bar-Chart}}
- Serie 1: 1, 3, 4, 2
- Serie 2: 2, 1, 2, 4


---
# Donut Graph
{{Donut-Chart}}
- a: 1
- b: 2
- c: 2.3
- d: 2
- e: 1
- f: 1.4


---
# Pie Graph
{{Pie-Chart}}
- a: 1
- b: 2
- c: 2.3
- d: 2
- e: 1
- f: 1.4

---
# Axis 1/2

- For the Y axis, scale and values are defined automatically based on the minimal and maximal values of your data.
- For the X axis, you can also let Slideas to calculate them automatically. However in the majority of cases, you will need to provide your own values.
- **Note**: Providing custom X axis value only make sense for graph types supporting multiple values per series. 



---
Layout: HeaderAndColumns
# Axis 2/2 
+++
You can set your own values for a graph by declaring an additional series having `x` as name: Example: 


{{spline-chart}}
- Budget: 120, 130, 150
- x: 2015, 2016, 2017

+++
X axis can have different type:
- By default it will use the numeric values provided
- You can also have categories : `x,categories: category one, category two`
- Or use the x axis as a timeline with `x,timeline:2020-01-01, 2020-02-01`
- For the timeline, you can use an optional format: `x,timeline,%Y-%m:2016-01-01, 2016-02-01`


---
Layout: SectionTitle

# Devices 📱
---
# iPhone

{{iphone}}
![](https://www.slideas.app/img/photos-background.jpg) 

---
# iPad

{{ipad}}
## Blocks are fun
	and can contain **Markdown**

---
# MacBook

{{macbook}}
![](https://www.slideas.app/img/photos-background.jpg)

---
# Browser
 Not really a physical device but...
 
{{browser}}
🦄

---
Layout: SectionTitle
# (Dynamic) Charts
---
# Grid


{{grid}}
With
	- List item 1
	- ... and Item 2
some **bold** 
simple content...
![](https://www.slideas.app/img/photos-background.jpg) 


---

# Sequence
{{sequence}}
Step 1
Step 2
Step 3
Step 4
