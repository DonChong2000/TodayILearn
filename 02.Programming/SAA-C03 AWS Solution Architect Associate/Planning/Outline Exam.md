 - Multiple choice and Multiple response (2 of 5 correct) only
 - no penalty for guessing
 - Total 65 questions, 15 unscored questions but not identified
 - Pass or fail exam
 - Score from 100-1000, passing is 720+, 80% up]

**Domain 1: Design Resilient Arc
hitectures - 30%**
這個章節要我們了解如何創建有效率的架構，利用 AWS 的基礎資源，如 EC2, VPC, RDS, S3 等，最好的練習是知道何時需要這些架構，建議閱讀 AWS Well-Architected Framework 了解更多。

**Domain 2: Design High-Performing Architectures — 28%**
這個章節的重點在於如何建構 resilient（有彈性、容易復原的）架構，利用 Scalability 和 Elasticity，我們需要了解 Multi-AZ 以及 Auto-Scaling 的原理及目的，以達到降低成本和優化容錯能力。

**Domain 3: Design Secure Applications and Architectures — 24%**
於此章節，我們需要了解如何利用 4 個面向（AWS resource, network-layer, application-layer, data-layer）添加安全措施，其中 Data-layer 又可以分成 2 個部分：data in transit & data at rest。資料安全中，加密佔了主要很重要的部分。至於 networking 的部分，我們需要知道權限控制，如 Security groups, Access Control Lists。

**Domain 4: Design Cost-Optimized Architectures — 18%**
最後一部分，我們需要知道如何打造低成本架構，並考量 scalability 和 resiliency，選擇正確的 AWS 資源，最後，懂得如何優化 network design 來有效率的從 on-premise 轉移資料到 cloud。