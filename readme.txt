code .
python -m venv .venv
.venv/Scripts/activate.ps1

#.ps1 檔案無法載入，因為這個系統上已停用指令碼執行
以系統管理員身份開啟 PowerShell ISE
輸入"set-executionpolicy remotesigned"
會跳出視窗，點擊"全部皆是"

#安裝streamlit
pip install streamlit

python.exe -m pip install --upgrade pip

streamlit run hello.py

https://docs.streamlit.io/get-started/tutorials/create-a-multipage-app

deploy
https://docs.streamlit.io/streamlit-community-cloud/deploy-your-app


sw.Write("\r\n");	//換行
sw.Write(System.Environment.NewLine); //換行