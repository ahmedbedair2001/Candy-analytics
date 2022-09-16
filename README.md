# Candy-analytics
<h1>Hello</h1>
<h2>Here we have a dataset of answers for official survey form for the 2017 Candy Hierarchy and our pupose is to get te top 10 loved and hated candies.but it has many irrelative and null values so we will clean it and drop some rows and I'll explain the steps of doing it on my way</h2>
<ol>
  <li> Dropping null values from q1</li>
  <li> Changed null values in q2 that talks about gender to I'd rather not say</li>
  <li> Transformed strange values in q3 that talks about ages to null and changed the age that was written by a text to numbers</li>
  <li> Changed null values in q3 to random values between(mean-(2*standard deviation) and mean+(2*standard deviation))</li>
  <li> Corrected writing mistakes in q4 that talks about countries and dropped some values that was misunderstood</li>
  <li> Dropped q5 that talked about cities because we certainly know their countries and q5 won't be so useful</li>
  <li> Transformed strange values in q6 that talks about opinions about candies to meh to make it doesn't effect on opinions about choclate </li>
  <li> Dropped columns from q7 to q9 ,q12 ang q13 because it seemed not very useful</li>
  <li> Transformed strange values in q10 that talks about clothes to White and gold because it was the most common value in the dataset </li>
  <li> Transformed strange values in q11 that talks about holidays to friday because it was the most common value in the dataset</li>
  <li> Collected informations about top 10 candies loved and hated from the number of people who see every king joyful or derpaired</li>
  <li> Visualized these information to horizontal bars</li>
</ol>
