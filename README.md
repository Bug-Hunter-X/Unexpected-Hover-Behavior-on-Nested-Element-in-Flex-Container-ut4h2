# Unexpected Hover Behavior on Nested Element in Flex Container

This repository demonstrates a CSS bug where the :hover pseudo-class on a nested element within a flex container unexpectedly applies to the parent element.

## Bug Description

When hovering over a nested element within a flex container, the hover effect applies to the parent container instead of the nested element. This happens because the parent flex container captures the hover event before it reaches the nested element. 

## Solution

The solution involves setting the pointer-events property of the parent element to 'none' or using a different approach to handle the hover event, such as utilizing JavaScript.