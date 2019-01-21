# Git-Command

* **Take Checkout**

      git clone url

* **Take Update**

      git pull
      
* **Revert Local changes not commited yet** 

      git checkout filename
* **Revert pushed single commit changes**

      git revert -n commit-id
      -n for no commit for revert 
  
* **Revert pushed Multiple commit without revert commit**
      git revert -n _oldest commit id_.._lastest commit id_
