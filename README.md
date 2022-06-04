# Whatsapp-Chat-Analyzer-Webapp

Prerequisites :

Before you can get started, ensure that the following packages are installed in your Python environment .
### Pandas
### Seaborn
### Matplotlib

## step 1.Data Collection
we require a whatsapp conversation to analyze. Open a whatsapp conversation you wish to analyze and use the “Export Chat” functionality to send the entire conversation in text format to your email ID.

Important Note: When prompted by whatsapp, ensure that you do not export any media otherwise it might take ages to export.


![whatsapp chat1](https://user-images.githubusercontent.com/68411214/171998796-b2e02e84-49e1-4df8-8f04-3018bc14de3e.png)

![chat2](https://user-images.githubusercontent.com/68411214/171998818-c2577d27-9f06-4edd-8645-058e6e46f252.png)

## Step 2. Data Preparation and Cleaning

In the data preparation we convert the data into a particular pattern using regular expressions. We remove the unnecessary information , null values , duplicate values. This is known as Data cleaning and then we convert text file into dataframe. 

## Step 3.Exploratory Data Analysis(EDA)

In the EDA we look at five important points to ask:
1. Overall statistics of the chat including total messages , total links , total medias sent etc.
2. Monthly & Daily timelines of the user message
3. Most busy day & most busy month of the group chat
4. Weekly Activity Map
5. Most Busy users ( who texts more ) and their text percentage
6. Wordcloud of most commonly used words.
7. Emoji Analysis

## Step 4.Visualization of Chat 

Visualization of the various statistics is done using the ## Streamlit App.

![TOP stats](https://user-images.githubusercontent.com/68411214/171999246-b445f1e9-f485-4f2a-ad0e-82c66ee8b5b1.png)

![monthly timeline](https://user-images.githubusercontent.com/68411214/171999251-c887a5c7-b384-43c0-8b8b-ea686686dd1d.png)

![daily timeline](https://user-images.githubusercontent.com/68411214/171999252-6b345126-25a5-40fe-b00b-5f1c4d9ef0f7.png)

![weekly activity map](https://user-images.githubusercontent.com/68411214/171999254-82464c1e-7b9a-49b0-a8ec-363cc34752e4.png)

![activity map](https://user-images.githubusercontent.com/68411214/171999257-b8b01aa9-4516-44e7-b0fc-109675189042.png)

![wordcloud](https://user-images.githubusercontent.com/68411214/171999272-2dc6f24f-9cf7-4bdf-8263-1b3c2bbac788.png)

![emoji analysis](https://user-images.githubusercontent.com/68411214/171999275-d67a26e5-f35f-41de-a7bb-47a0e504a2cc.png)

![most busy users](https://user-images.githubusercontent.com/68411214/171999330-9f536f51-45d5-4e23-918b-e3db45c63e2f.png)



