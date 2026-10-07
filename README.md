# Blog 01: Title and Introduction
Hello folks,

What's up! My name is Saad, and I'm an AI & DS student from APCOER Pune. Today is 7th October, and I’m writing this blog manually—yes, in the age of AI! This is part of my Lab 08 assignment, where I learned some new algorithms in Machine Learning.

So, I hope you’re interested in reading my first blog on GitHub!

In today’s project, I experimented with machine learning algorithms, which I’ll be discussing here.

## What did I do?

Basically, I used Python to implement the K-Means Clustering Algorithm. First, with the help of make_blobs, I created a fake dataset with more than 300 points, specifying 4 centers.

# Observations :

## Observation 1 

<img width="589" height="455" alt="download" src="https://github.com/user-attachments/assets/2f7b742e-47b4-4fb3-b3c3-b7ad0d993c04" />

IF i talk about Elbow Graph , in that case Value of WCSS at k =2 was 11000 + and it was dropped to 2200+ at k =4 , learn that at k = 4 method was saying 4 was great!

## Observation 2 

<img width="347" height="470" alt="download (1)" src="https://github.com/user-attachments/assets/a4726694-56af-44ce-8a23-31f1d0ea931f" />

If i talk about Silhouette Graph when i ploted that graph i fill were unexpected and the result was insane , k =3 was highest point if i was comparing k = 4

# *3* Why did this happen?  

<img width="678" height="528" alt="download (2)" src="https://github.com/user-attachments/assets/d6282391-2e08-4610-a7c9-6cb5d5efab45" />

toh mujhe dikha ki upar wale do clusters (Purple aur Yellow) ek doosre ke bohot kareeb hain aur thode touch ho rahe hain. Is wajah se Silhouette score ko laga ki in dono ko mila kar 1 bada cluster bana dena chahiye (total 3 clusters)

# Conclusion / What I Learned : 

is lab se maine seekha ki hamesha kisi ek score (jaise sirf Silhouette Score) par bharosa nahi karna chahiye. Hamesha data ko plot karke (visually) aur do-teen methods mila kar hi final decision lena chahiye















