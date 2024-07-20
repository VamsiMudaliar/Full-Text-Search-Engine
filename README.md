# Full-Text-Search-Engine

Implementing a full text search engine service, 
It scans huge data and builds inverted index while applying various processing techniques like tokenisation, removing stop words and applying stemming. 

To Get started, follow these simple steps. 

get the data dump from - 

    https://dumps.wikimedia.org/enwiki/latest/enwiki-latest-abstract1.xml.gz

Clone the repo 
    
    git clone https://github.com/VamsiMudaliar/Full-Text-Search-Engine.git`
  
Place the installed compress file in the root folder of the project. 

Run this command, also add your own way of taking the input. 

    go run main.go

Below are some Performance metrics, upon loading 683048 documents, converting index and performing a full text search. You can see the time taken to search the given input in these huge documents 

  <img width="1379" alt="Screenshot 2024-07-20 at 11 54 58 PM" src="https://github.com/user-attachments/assets/18d3daaf-94f0-4d7c-836e-5eb3cebc437a">
