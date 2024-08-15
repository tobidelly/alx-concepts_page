# Flowcharts

## What is a Flowchart?

A flowchart is a type of diagram that visually represents a workflow or process using a set of symbols or icons to denote different actions/decisions/steps within the process with arrows showing the direction of the flow. Flowcharts are used across many different professions to help analyze, design, document, and/or manage a workflow or process.

## Why use a Flowchart?

Similarly to pseudo-code, flowcharts provide another way of approaching and/or understanding a workflow. Another benefit is that, when done well, flowcharts can be understood by non-developers and by developers that do not know the language the process is written in.

## Flowchart Symbols

This type of diagram is extremely versatile and is used across many professional fields. Due to the number of industries using flowcharts, many sets of symbols and styles have been created with a specific industry in mind. A good symbol set to use is the ISO 5807 symbol set, as they are well-known and often used in the technology industry.

### Some commonly used ISO 5807 symbols

| Symbol | Name | Description |
| --- | --- | --- |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/5bc2a924f79c536f50da.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2d520dce273a10ad79b472980af466e3c0ee924859af35f01a92b2e5319aad24) | Flowline / Arrowhead | Shows the order. Comes from one symbol to another |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/63feb920c4666f09326a.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c8c4493e264b952f7fc599da3226d8dfbc0d1516ebeabaa24046f1bd81632b63) | Terminal / Terminator | Shows where a process (or sub-process) starts or ends; text is usually “Start”, “Begin”, or “End” |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/0c14df72f5d58bdccffa.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=721c216cc3f94d8a615b420a7594eb903e496f9b7a951d21381129a75ce96d37) | Process / Rectangle | Process, action step, or operation; text is usually a verb, examples include: “Edit Video”, “Choose Plan”, “Set variable to ‘hello’” |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/61cb6f6432e289663024.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a0d2461e8353b0256450fc34af329946896acde08a76a46ac4e2912da65725bc) | Data (I/O) | Inputs to (entering data) and Outputs from (displaying results) a process |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/8d6224b7a302d4aea92f.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7ab2213908c97fd3476f26647aec30a64c30e9e26763061cca6e5f6e58ccbc1c) | Decision / Conditional | Used to ask a question whose answer determines the route taken from the question. Arrow from bottom is Yes / True, Arrow from side(s) is No / False, (Always label the arrows to make it clear) |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/d6a5c9521182bd1db22b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=528010062f581427c4c8697b8c3b50a28f3c7e2ab92ad4557a97971b6714ff9c) | Document (s) | Represents a document or report |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/899ad233b3a3285af0b1.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=98bc4fc384683c3dd2e22a22780d2da1cbcda89303d8b6bc6282f2ecd75eb469) | Subroutine / Predefined Process | A process that can be used in the current process but defined elsewhere (should have a separate flowchart for it) |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/745f08c52be8f7686926.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7c6eaf41f8e2588b99bcd2ef48b65d04129b7c0907482e6896487eaacb9e7b61) | Annotation (Comment) | Additional info about a step; the line connecting to the step can be solid or dashed |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/b0ed5e74d8e279c15819.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8ea697ac0e160d061137adcf1bf9ebdd19d376b81fc2337ba49766be8dc951b1) | On-page Connector | Replaces long or confusing lines, use a letter to reference |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/0619bb11497a0bfb4f35.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=560bf9ca10d2a7909575e9b3fc68c1a4c4f08083dc6fca3fa5b31116f7ad692e) | Off-page Connector | To connect this process to the next step, which is on another page; use page number for reference |
| ![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/78884262285c367ee630.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=05ded33d232425d032e36584acba89edb816ddd3b7334e3dd860bc33420f816e) | Data File / Database | Data represented by a cylinder (originally representative of disk drive) |

## An Example

Let’s think about Foundation task, and include a flowchart example for it:

The task instructions are as follows:

> Write a function that draws a straight line in the terminal.
> 
> -   Prototype: void print\_line(int n);
> -   You can only use `_putchar` function to print
> -   Where `n` is the number of times the character `_` should be printed
> -   The line should end with a `\n`
> -   If `n` is 0 or less, the function should only print `\n`

Take a moment to write out a solution in pseudo-code.

  
  
  
  
…  
  
  
  
No, really. It’s good practice. :)  
  
  
  
…  
  
  
  
Okay. Below is what I came up with.

1.  Set a variable equal `n` (`int nCopy`)
2.  Set up a while loop (condition: `nCopy` is greater than 0)
3.  Print `-`
4.  Decrease `nCopy` by 1
5.  Print `\n`  
      
    

Now, using the ISO 5807 symbols from the table above, draw out a flowchart for this function.  
  
  
  
…  
  
  
  
No peeking!  
  
  
  
…  
  
  
  

Alright, does your flowchart look similar to the diagram below?

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/8/fb82e24f7282c569aed3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20240815%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240815T013314Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9319ef945ee3bac8ab2dfd4531cffd8461034b3144605f49cef633c2d6ea91bb)

## Bonus Info

Some good uses of flowcharts:

-   Create a flowchart before coding a task to either help create or validate pseudo-code
-   Add to a README.md to visually show how your project/process works
-   Use in a presentation to aide audience understanding
-   Your function or process is not working as expected? Create a flowchart of how it CURRENTLY is. Then, walk through the chart with some example input.

A flowchart can be as high-level or as detailed as you want. For example, you could break the flowchart above down further to include what is happening in memory. You can even create flowcharts from your everyday non-technical experiences. Choosing a movie or a place to eat could be displayed as a flow-chart!

A helpful tool to create flowcharts is [draw.io](https://intranet.alxswe.com/rltoken/aOmwlxIhyIzTDorIC5SNWA "draw.io"). There are premade symbols for you to use and your diagrams can be saved to your Google Drive.

For more information on Flowcharts and related diagrams, a google search with simply “flowchart” can get you started. ;)