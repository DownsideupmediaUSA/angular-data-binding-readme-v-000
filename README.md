# Data-binding

## Overview

In this lesson we're going to go a bit deeper into the `{{ }}` curly brace syntax you've seen. What does it actually do?

## Objectives

- Describe one/two-way data-binding in `$scope`

## Data-binding

We've talked about data-binding before, but if it's not on the top of your memory you don't need to worry. Data-binding is the term for keeping our model values in sync with our view. Whenever the model changes, our view needs to change too to reflect the change. Whenever our view changes (such as a user typing into an input), we need to update our model with the latest value. This is done via data-binding.
 
The curly braces syntax (`{{ }}`) binds our model value into our view in the form of text. This is one-way bound - the model can update the view, but our view cannot update the model (you can't type into text - only an input!).

