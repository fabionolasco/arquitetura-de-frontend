# Accordion
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

## Author
Fabio Nolasco <contact@fabionolasco.com>

## Minimum required code
<fn-accordion>
    <fn-a-item title="Title">Content</fn-a-item>
</fn-accordion>

## Use Case 1
<fn-accordion openOneAtATime="true">
    <fn-a-item title="Title 1" isOpened="true">Content 1</fn-a-item>
    <fn-a-item title="Title 2">Content 2</fn-a-item>
    <fn-a-item title="Title 3">Content 3</fn-a-item>
    <fn-a-item title="Title 4">Content 4</fn-a-item>
</fn-accordion>

## Inputs
>> fn-accordion
    - openOneAtATime: boolean
        - Default false
>> fn-a-item
    - isOpened: boolean
        - Default false
    - title: string
        - Default empty
    - icon: string
        - Default 'arrow'
        - Other options: clock, tree, like, dislike

## Output
>> fn-accordion

## Requirements
- Icon can be selected to be on right or left
- Panels can selected to be opened just one at a time or multiple at a time.

# Known issues
- Can't take HTML content on title
