# Business Hours Steps

This step allows you to find if it is currently business hours or not. With a switch you can do different things based on if the time currently fits your time constraint.

---------

<kbd>
  <img src="https://github.com/xmatters/xMatters-Labs/raw/master/media/disclaimer.png">
</kbd>

---------

# Files
* [IsitBusinessTime.zip](IsitBusinessTime.zip) - Workflow zip file with the step and example flow

# How it works
The step checks if it is currently business hours. It takes in the timezone in order to make sure the times are local to wherever you are (e.g. US vs. India).

# Installation

## xMatters Setup
1. Download the [IsitBusinessTime.zip](IsitBusinessTime.zip) file onto your local computer
2. Navigate to the Workflows tab of your xMatters instance
3. Click Import, and select the zip file you just downloaded


## Usage
The **Is It Now Business Hours?** step is now available in your custom steps. So navigate to the appropriate canvas so you can add the step there. If you'd like to experiment with it, the **A Form** workflow has a canvas that can be triggered via HTTP call. 


### Inputs
| Name  | Required? | Help Text | Default Value | Multiline |
| ----- | ---------- | --------- | ------------- | --------- |
| Timezone Offset | Yes | The number of hours from GMT in +dd:dd format. -8:00 is pacific time. | -08:00 | No |
| Business Hours Start | Yes | The start time of the business day in 24 hour clock. | 09:00 | No |
| Business Hours End | Yes | The end time of the business day in 24 hours clock. | 17:00 | No |
| Business Days | Yes | A comma separated list of the business days, Sunday-Saturday : 0 - 6 | 0,1,2,3,4 | No |


### Outputs

| Name | Description |
| ---- | ----------  |
| Result | Whether it is business hours or not (Yes/No) |


## Example

<kbd>
  <img src="/media/ExampleFlow.png">
</kbd>

