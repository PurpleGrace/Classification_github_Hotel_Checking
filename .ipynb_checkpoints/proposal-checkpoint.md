# Classification project
## Will this booking for hotel will be canceled?

### Question/Need:

- What is the question behind your analysis? What is the purpose of the model/system you plan to build?

<span style="color:lightseagreen">
This Analysis predict if a booking for hotel will be canceled or not. The purpose of the project is help hotels to identify the bookings with potential of cancelation through classification models, explore the relationship between cancelation and features of booking, provide insight or suggestions for hotels to adopt measurement to decrease cancelation rate, so that to improve operating profit.

</span>

- Who benefits from exploring this question or building this model/system?

<span style="color:lightseagreen">
Any hotel in the hotel industry will be able to benefits from building this model, given that it is able to collect pertinent data。
</span>


### Data Description:

- What dataset(s) do you plan to use, and how will you obtain the data?

<span style="color:lightseagreen">
  This dataset contains 119390 observations for a City Hotel and a Resort Hotel. Each observation represents a hotel booking between the 1st of July 2015 and 31st of August 2017, including booking that effectively arrived and booking that were canceled.
  
</span>

- What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?

<span style="color:lightseagreen">
Each row of the dataset is a booking record with target "is_canceled" and tens of features with detail information, like booking time/date/duration, guest numbers, room type and etc.
</span>

- If modeling, what will you predict as your target?

<span style="color:lightseagreen">
In the modeling, the target will be "is_canceled", 1 represents "canceled", while "0" represents not.
</span>


### Tools:

- How do you intend to meet the tools requirement of the project?

1. python
2. numpy, pandas for data manipulating
3. seaborn, matplotlib for data visualization
4. sklean for classification modeling

- Are you planning in advance to need or use additional tools beyond those required?

<span style="color:lightseagreen">
Tableau might be used for EDA visualization.
</span>


### MVP Goal:

What would a minimum viable product (MVP) look like for this project?

<span style="color:lightseagreen">
The MVP for the project will provide a baseline classification model to predict if a booking will be canceled.
</span>
