**GitHub.HW_2**  
   
    git init HW_2  
    cd HW_2  
    touch Readme.md  
    git status    
    git add .    
    git commit -m "add Readme.md"  
    git branch -M main    
    git remote add origin https://github.com/AlenaAndros/GitHub.HW_2.git    
    git push -u origin main  
***
1. На локальном репозитории сделать ветки для:
- Postman //        `git branch Postman`
- Jmeter  //        `git branch Jmeter`
- CheckLists //     `git branch CheckLists`
- Bug Reports //    `git branch Bug_Reports`
- SQL     //        `git branch SQL`
- Charles //        `git branch Charles`
- Mobile testing // `git branch Mobile_testing`
***
2. Запушить все ветки на внешний репозиторий //  `git push -u origin --all`

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта //     

        git checkout Bug_Reports     
        touch Bug_Reports.txt  
        vim Bug_Reports.txt
        I
        
 **№** | **ID** | **Samary** | **Description** | **Requirement id** | **STR** | **Actual Result** | **Expected Result** | **Priority** | **Severity**  
 ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
 
    Esc
    :wq
       
4. Запушить структуру багрепорта на внешний репозиторий  

        git add .  
        git commit -m "add Bug_Reports"  
        git push  
 
5. Вмержить ветку Bug_Reports в Main  

        git checkout main  
        git merge Bug_Reports  
        
6. Запушить main на внешний репозиторий //  `git push`

7. В ветке CheckLists набросать структуру чек листа.

        git checkout CheckLists     
        touch CheckList.txt  
        vim CheckList.txt
        I       

**№** | **ID** | **The Idea of Verification** | **Comments**   
 ---- | ---- | ---- | ---- 
 
    Esc
    :wq

8. Запушить структуру на внешний репозиторий

        git add .  
        git commit -m "add CheckList"  
        git push  
        
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

        Compare & pull request  
        Create pull request  
        
10. Синхронизировать Внешнюю и Локальную ветки Main

        git checkout main  
        git pull

