# Uncommon HTML Bug: Incorrect div content modification

This repository demonstrates a subtle bug related to modifying the content of a div element in HTML.  The issue arises from an incorrect approach to updating the div's text, leading to unexpected behavior. The solution showcases the proper method of updating the content using either `innerHTML` or `textContent`.

## Bug Description

The bug lies in attempting to directly set the content of a div element without using the appropriate methods (`innerHTML` or `textContent`).  While seemingly straightforward, this approach can fail to update the content correctly. 

## Bug Solution

The solution file shows how to correctly update the div's content using both `innerHTML` (for inserting HTML markup) and `textContent` (for inserting plain text).