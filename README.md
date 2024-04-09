# Bouncing_Ball_Game
# 資料夾說明
* 彈跳球遊戲:
  * 遊戲說明: 玩家需要用滑鼠操作一個會隨滑鼠X座標移動的版子在有限空間內去控制不斷撞到物體而反彈的球撞到所有在空間內的方塊,越快撞完的人獲勝
  * 結合HTML與CSS做出遊戲畫面,再利用Javascript物件導向概念做出磚塊物件
  * 遊戲畫面:
    * <img height="400" width="300" src="https://github.com/nickchen111/Bouncing_Ball_Game/blob/main/img/%E5%BD%88%E8%B7%B3%E7%90%83.png">
    可以從github page實際操作
  * 技術細節:
    * 在判斷是否所有磚塊被消除的程式碼中,不去真的將陣列中的磚塊物件刪除 而是用一個變數count計算被撞擊的磚塊再利用visible屬性去讓磚塊消失 以此來優化時間複雜度
    * 利用canvas做出遊戲畫面
# English Version
* Bouncing Ball Game:
  * Game Description: Players need to control a paddle that moves horizontally with the mouse to bounce a ball continuously hitting objects within a limited space, aiming to hit all t      -he bricks in the space. The faster player who clears all bricks wins.
  * Created the game interface using HTML and CSS, then utilized JavaScript's object-oriented concepts to create bricks objects.
  * Game Interface:
  * <img height="400" width="300" src="https://github.com/nickchen111/Bouncing_Ball_Game/blob/main/img/%E5%BD%88%E8%B7%B3%E7%90%83.png">
  
    You can also use the GitHub page to try it out.
  * Technical Details:
    * In the code for checking if all bricks have been eliminated, instead of deleting bricks objects from the array, a variable "count" is used to track the number of hit bricks. The
      "visible" attribute is then used to make bricks disappear, optimizing time complexity.
    * Utilized canvas for creating the game interface.
