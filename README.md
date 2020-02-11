# Business Hours Steps

This step allows you to get the commit details from a given repo and user. Great for enriching notifications with relevant code commit information. 


---------

<kbd>
  <img src="https://github.com/xmatters/xMatters-Labs/raw/master/media/disclaimer.png">
</kbd>

---------

# Files

* [IsitBusinessTime.zip](IsitBusinessTime.zip) - Workflow zip file with the step and example flow

# How it works


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
| Timezone Offset | Yes | The number of hours from GMT in +dd:dd
format. -8:00 is pacific time. | | No |
| Business Hours Start | Yes | The start time of the business day in 24 hour
clock. | No |
| Business Hours End | Yes | The end time of the business day in 24 hours
clock. | | No |
| Business Days | Yes | A comma separated list of the business days,
Sunday-Saturday : 0 - 6  | No |


### Outputs

| Name | Description |
| ---- | ----------  |
| Result | Whether it is business hours or not |


## Example

<kbd>
</kbd>

