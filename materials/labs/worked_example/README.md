# 四步實作成果範例

這組檔案由 Step 1 → Step 4 依序承接同一份候選清單，用來檢查手冊能否照做。先自己練習，再拿來比較；不必和範例選出相同疾病或得到相同答案。

| 步驟 | 成果 | 如何閱讀 |
|---|---|---|
| 1 | [01_candidates_tw.csv](01_candidates_tw.csv) | 22 個候選與固定編號；有具名來源，也有待查欄位 |
| 2 | [02_background_tw.csv](02_background_tw.csv) | 22 個疾病 × 30 個欄位的長表；缺口列也保留 |
| 3 | [03_review_22_to_10.csv](03_review_22_to_10.csv) | 每個候選的 AI 整理紀錄；本範例尚待人工處置，正式審查結果保持空白 |
| 4 | [04_questions.csv](04_questions.csv) | C1–C5 題目規格、試填結果與資料限制 |

各步的實際操作、修正與驗收見 [Step 1](step1_execution.md)、[Step 2](step2_execution.md)、[Step 3](step3_execution.md)、[Step 4](step4_execution.md) 執行紀錄。下載與 CSV 存檔方式見[共通操作](../README.md)。

來源日期、涵蓋區域與條件決定資料能回答哪一題。若來源提供「腦炎患者致死率」，不能直接用來回答「所有感染者未治療致死率」。缺口可以是完整的課堂成果，但不能改成零、最低分或猜測值。

**這些檔案不代表機關核定清單或正式排序。** 第三步的演練選樣與人工審查程序須分辨，第四步的 C5 保持資料缺口、不計分。需要正式確認的事情，不能由 CSV 填滿或自動測試通過來取代。

為了讓 Step 4 的程式流程可被測試，另有 [03_step4_flow_test_selection.csv](03_step4_flow_test_selection.csv)。它固定列出十個 ID，且每列標明「純流程測試選樣、無優先意義、未經人工核定」；它不是課堂選樣，也不回填到 Step 3 的人工欄位。

第四步另附 [50 筆逐題試填](04_trial_answers.csv)與[待確認事項](pending_items.csv)，可逐列核對題目表的分布。
