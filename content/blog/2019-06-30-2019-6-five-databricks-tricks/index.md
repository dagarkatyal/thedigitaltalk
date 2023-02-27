---
title: "5 Things to get best out of Azure Databricks"
date: "2019-06-30"
categories: 
  - "big-data"
  - "cloud"
  - "tips"
tags: 
  - "azure"
  - "big-data"
  - "concurrency"
  - "data-engineering"
  - "databricks"
  - "modern-data-platform"
  - "tips"
cover:
    image: "images/img-2.jpg"
---



Most of the customers I talk to are directly of indirectly asking to to scale their workloads and use Databricks. It has become the new normal in the data processing in cloud. If you are using or plan to use Azure Databricks, this post is will guide you on some interesting things that you can plan to investigate as you start. I have not touched any technology in this but is good for developers/architects to know these things

1. **Use interactive cluster**: Teams spend lot of time playing with data and exploring the patterns. There is a certainly a need to have a unobstructed compute and horsepower available while users are exploring the data, or while developers are working on the notebooks. It’s great to have a interactive cluster available for developers or end users for such scenarios. 
    
2. **Use job clusters**: while your jobs or notebooks are running in production there are optimizations around costs that can be achieved using job clusters. These clusters spin up for the job run-time only, provide the compute and decommission automatically once the job is done. Whether you are scheduling in azure Databricks or orchestrating from tools such as Data factory, job clusters provide a great way to optimize cost and resources in production 
    
3. **Use shortcuts**: there are lot of shortcuts available in notebooks and the list can be accessed from within the notebooks. You won’t remember all but here is list of my favorite ones which makes thing super easy
    
    1. Shift +Enter: use this to run the command and switch the control to next cell. Best thing is that it inserts a new cell if you are at the end of the notebook
        
    2. Ctrl + /: this is by far the most used shortcut. This comments/ un-comments the code in the cell. Best thing is that, depending upon on the magic commands you used it uses the right comment format (either ‘/’ or ‘- -’ or ‘#’) for the language 
        
    3. Hold Shift key: Hold the key while deleting the cell. This will stop annoying pop up confirmation to delete the cell
        
    4. [For more shortcuts refer the link](https://docs.databricks.com/user-guide/notebooks/notebook-use.html)
        
4. **Use magic commands**: I like switching the cell languages as I am going through the process of data exploration. Having come from SQL background it just makes things easy. And there is no proven performance difference between languages. All languages are first class citizens. Feel free to toggle between scala/python/SQL to get most out of Databricks. [Refer this link for more](https://docs.databricks.com/user-guide/notebooks/notebook-use.html#mix-languages) 
    
5. **Use Databricks Delta**: this is by far the best feature of the technology that is going to change the way data lakes are perceived and implemented. Delta provides seamless capability to upsert and delete the data in lake which was crazy overhead earlier. Using delta is going to change how lakes are designed.
    
    For more info on delta and delta lake. Look for my next blog.
