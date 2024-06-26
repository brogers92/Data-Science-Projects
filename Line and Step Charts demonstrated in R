getwd()
setwd("/Users/bryansmacbookpro/Desktop/Data Projects/R Files/Run Data.csv")
getwd()
setwd("/Users/bryansmacbookpro/Desktop/Data Projects/R Files/")
getwd()
run_data <- read.csv("run data.csv")
library(ggplot2)
ggplot(run_data, aes(x = Year, y = Distance)) +
  geom_line(color = "blue") +
  labs(title = "Line Chart - Pace Over Time", x = "Date", y = "Distance") +
  theme_minimal()

ggplot(run_data, aes(x = Year, y = Distance)) +
  geom_step(color = "orange") +  
  labs(title = "Step Chart - Pace Over Time", x = "Year", y = "Distance") +
  theme_minimal()
