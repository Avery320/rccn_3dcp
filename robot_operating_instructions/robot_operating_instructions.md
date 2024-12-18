# 機械手比操作說明

## 機器人開機
本次專案使用raccoon工廠內的West Robot，與混凝土擠出機，開幾步驟為：
1. 打開總電源。
2. 於kuka控制箱上將機器人開機。
3. 在控制箱上將混凝土擠出機開機。
4. 將機器人個軸移動到適當位置，安裝混凝土擠出機。
   - **移動時要時刻注意，避免手臂上電箱與泵送系統的支撐柱碰撞。**
5. 測試並確認混凝土擠出幾可以順利運行。

## 機器人關機
1. 拆下混凝土擠出幾。
2. 將機械手臂回復成力臂較小的姿態。
   - **移動時要時刻注意，避免手臂上電箱與泵送系統的支撐柱碰撞。**
3. 關閉教導版，教導版成功關機後，關閉kuka控制箱電源。
4. 關閉混凝土擠出幾電源。
5. 關閉總電源。

## 機器人控制
機器人開機後使用T1模式運作。
1. 輸入密碼：於教導板上開啟`configeration`->`user group`->`選取expert`->`輸入密碼`。
2. 開啟west share>點選執行檔案>點選下方edit列表duplicated檔案至指定資料夾->rccn_test以edit paste。
3. 選擇運行檔案以`seclect`執行檔案，手持按壓綠色執行鈕，手臂歸位至檔案指定初始點位。
4. 當案初次以T1(手動)模式進行測試，測試時請務必確保機器人速度，測試完成後才可以Auto(自動)模式進行列印。
5. 列印時教導版請勿離開手邊，避免警急情況發生，無法及時處理。
6. 工作空間有配置光柵系統以確保工作執行上的安全，作業中若有人闖入環境中會觸發使機器人停止運行，工作時請架起三角錐或設立告示牌，以避免人為情況造成實驗失敗。
