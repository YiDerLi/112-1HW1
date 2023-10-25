# 第1次作業-作業-作業1
>
>學號：111111124
><br />
>姓名：李羿德
><br />
>作業撰寫時間：210 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/10/25
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容

最先是以Git Bash設定使用者及電子郵件以獲取SSH的金鑰(git config --global user.name “John Doe”；git config --global user.email johndoe@example.com)，方便日後無須再額外做個人喜好設定。
<br>
再來去校網抓取老師給予的檔案，並且完成下載延伸模組及抓取作業檔案(git clone 位址)。
<br>
之後開始製作主線上的a.txt檔，輸入內容後加入資料變動(git add a.txt)並提交資料(git commit)，最後將完成的更新推送至自己的Github倉庫(git push)。
<br>
隨後在主線上製作一個分支testdiv(git branch testdev)，切換至分支(git checkout testdev)並在其中建立b.txt的檔案，並且做與上述相同的動作，推送完成後切換回主線(git checkout main)。
<br>
在主線上建立同名為b.txt的檔案，除了與上述所輸入的內容不同外，其餘相同且完成推送(git push)。
<br>
最後將分支與主線合併(git merge testdev)後，將檔案推送至伺服器端倉庫(git push --set-upstream origin testdev)，完成作業後將其更新並推送(git add answer.md；git commit；git push)。

## 個人認為完成作業須具備觀念

此作業需熟知Github和VScode之間相互連接的方法，以確保資料能正確推送及拿取；須了解如何在主線上製作一個甚至數個分支，使資料庫能有多種不同的可能性。
<br>
上述兩點主要是為了讓諸位同學們熟悉兩者間的操作，且更加方便設定個人作業時的喜好設定，以養成最基本的習慣並方便日後的工作。