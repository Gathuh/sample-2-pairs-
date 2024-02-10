

x <- c("John","Kiruma samuel","Gathu Macharia","Maxsimon Ndungu","Wanza Faith","Faith Kathambi","Mutuma")
b=11:17
data.frame2=data.frame(x,b)
n <- length(x)

while (n >= 2) {
  group <- sample(data.frame2, 2, replace = FALSE)  # Ensure sampling without replacement
  n <- n - 2
  cat(group[1],"    and    ", group[2],"\n")
  indices <- which(x %in% group)  # Find indices of elements in x that are equal to any element in group
  x <- x[-indices]  # Remove elements from x based on their indices
}

cat('Oops "bona fide student": ',x,' you did not get yourself a partner')

