**日本語**

PDFデータスクレイピングRPA（請求書データ入力自動化）
  このプロジェクトは、PDF請求書からデータをExcelスプレッドシートにコピー＆ペーストする作業を自動化します。ロボットは1000枚の異なる請求書に対してこの作業を1000回繰り返し、ヒューマンエラーのリスクを排除し、8倍の速度で作業を完了します。

プロジェクト概要
  PDFデータスクレイピングRPAロボットは、指定されたフォルダ内のすべてのPDFファイルをループし、必要なテキストを抽出して、Excelスプレッドシートにデータを貼り付けます。抽出が成功した場合、PDFファイルは「成功」フォルダに移動され、エラーが発生した場合は「失敗」フォルダに移動されます。このロボットは、この繰り返し作業を完全に自動化し、100％の精度で作業を行い、大幅な時間短縮を実現します。

動作の流れ
  PDFのループ処理: ロボットは指定されたフォルダ内のすべてのPDFファイルをループします。
  テキスト抽出: 各PDF請求書から必要なテキストをスクレイピングします。
  Excelへの貼り付け: 抽出したテキストをExcelの対応するセルに貼り付けます。
  ファイルの処理: 抽出が成功した場合、PDFファイルは「成功」フォルダに移動され、エラーが発生した場合は「失敗」フォルダに移動されます。
  速度と精度: このプロセスは、ヒューマンより8倍速く、エラーゼロで完了します。

プロジェクトファイル
  PDFデータスクレイピングRPAシナリオ説明書.pptx: プロジェクトの詳細とRPAシナリオの説明を記載した資料です。
  PDFデータスクレイピングRPA実行動画.mp4: AI Indeed RPAツールを使用してRPAプロセスが実行される様子を示す動画です。

必要条件
  AI Indeed RPAツール（プロセス実行用）
  請求書データを含むPDFファイル
  Excel（抽出したデータを貼り付けるため）

使用方法
  このリポジトリをローカルマシンにクローンします。
  PDFデータスクレイピングRPAシナリオ説明書.pptxを開き、詳細なRPAプロセスを確認します。
  PDFデータスクレイピングRPA実行動画.mp4を視聴して、RPAプロセスが実行される様子を確認します。



**English**

PDF Data Scraping RPA (Invoice Data Entry Automation)
  This project automates the tedious task of copying and pasting data from PDF invoices into an Excel spreadsheet. The robot performs this task 1000 times for 1000 different invoices, without the risk of human error, and at a speed 8 times faster than a human.

Project Overview
  The PDF Data Scraping RPA robot loops through every PDF file in a designated folder, extracts the necessary text, and pastes the data into a spreadsheet. If the extraction is successful, the invoice file is moved to the "Success" folder. If there is an error during the process, the file is moved to the "Fail" folder. This robot completely eliminates the manual effort of this repetitive task, ensuring 100% accuracy and saving significant time.

How It Works
  Loop through PDFs: The robot loops through all PDF files in the specified folder.
  Text Extraction: It scrapes the necessary text from each PDF invoice.
  Paste into Excel: The extracted text is then pasted into the corresponding cells of an Excel spreadsheet.
  File Handling: The robot moves the PDF file to the "Success" folder if the extraction is successful or to the "Fail" folder if an error occurs.
  Speed and Accuracy: This process is 8 times faster than a human and guarantees zero errors.

Project Files
  PDF Data Scraping RPAシナリオ説明書.pptx: Detailed information about the project and the RPA scenario.
  PDF Data Scraping RPA実行動画.mp4: A video demonstrating the RPA process in action using the AI Indeed RPA tool.

Requirements
  AI Indeed RPA tool (for running the process)
  PDF files containing invoice data
  Excel (for pasting the extracted data)
         
How to Use
  Clone this repository to your local machine.
  Open PDF Data Scraping RPAシナリオ説明書.pptx to review the detailed RPA process.
  Watch PDF Data Scraping RPA実行動画.mp4 to observe the RPA process in action.
