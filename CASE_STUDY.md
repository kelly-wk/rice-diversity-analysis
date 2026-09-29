# イネ多様性の多変量解析 / Multivariate Analysis of Rice Diversity

[紹介ページを開く / Open the presentation page](https://kelly-wk.github.io/rice-diversity-analysis/)

> **解析設計修復済み・方法のみ公開 / Analysis design repaired · methods only**  
> 公開ケーススタディ / Public case study

## 概要 / Overview

アクセッションIDの整合性を修復し、回帰・PCA・クラスタリングを複数の妥当性軸で再評価した解析。

A repaired diversity analysis preserving accession identity across regression, PCA, clustering, and multi-axis validation.

## 主なポイント / Highlights

1. **行番号とアクセッションIDを混同する結合バグを特定して修正。**  
   Identified and corrected a join bug that confused row numbers with accession IDs.
2. **一対一結合で実在IDを全工程に保持し、サンプル追跡性を回復。**  
   Restored sample traceability by preserving real IDs through one-to-one joins.
3. **内部指標、再標本化安定性、生物学的ラベル整合性を分けてクラスタを検証。**  
   Validated clusters separately by internal indices, resampling stability, and biological-label agreement.

## 研究の流れ / Research Flow

| 段階 / Stage | 内容 / Evidence |
|---|---|
| **課題 / Problem** | ID不整合を修復し、イネ多様性の低次元構造と群分けを過大解釈せず再評価する。<br>Repair identifier integrity and reassess low-dimensional structure and grouping in rice diversity without overclaiming. |
| **方法 / Method** | 頑健回帰、PCA、複数クラスタ法を、ID保持パイプライン上で実行する。<br>Run robust regression, PCA, and multiple clustering methods in an ID-preserving pipeline. |
| **検証 / Validation** | ブートストラップ安定性、内部指標、既知ラベルとの対応を独立に確認する。<br>Assess bootstrap stability, internal indices, and alignment with known labels independently. |
| **成果 / Outcome** | 追跡可能な解析へ修復し、クラスタを真の分類ではなく探索的構造として報告。<br>Restored a traceable analysis and reported clusters as exploratory structure rather than ground-truth classes. |

## 使用手法 / Methods

Python, Robust regression, PCA, Bootstrap, k-means, k-medoids, Hierarchical clustering, Biological-label validation

## 限界と適用範囲 / Limitations & Scope

- 原データはCC BY-NC-ND 3.0条件で、ローカルの正規化データと派生数値を再配布できない。  
  The source is under CC BY-NC-ND 3.0 terms, so local normalized data and derived numeric results are not redistributed.

## 公開範囲 / Publication Boundary

公開ページは方法と修復内容の要約のみ。非営利・改変禁止を含むライセンス境界のため、データ、実ID、コード、図、派生数値は公開しない。

The public page contains only a method and repair summary. Because the license includes noncommercial and no-derivatives restrictions, data, real IDs, code, figures, and derived numbers are not published.

---

この文書は公開可能な範囲だけで構成されています。  
This document contains only material cleared for public presentation.
