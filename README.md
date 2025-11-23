This project analyzes customer reviews of the iPhone 14 to uncover user sentiment and identify
major themes in customer feedback. Using a Kaggle dataset that contains reviews from different
regions and platforms, we applied a combined approach of LDA topic modeling and VADER sentiment
analysis to extract meaningful insights for product development and marketing strategy.

After preprocessing the data by removing non-English and low-information reviews, we conducted
LDA topic modeling and identified four key themes: camera performance, battery performance,
iPhone brand perception, and delivery service. We then integrated sentiment scores with topic
results to understand how customers feel about each area. The analysis shows that most camera-
related and brand-related reviews are positive, while battery performance and delivery issues
receive comparatively more negative sentiment.

Our findings highlight clear improvement opportunities for Apple, particularly in battery
lifespan, delivery reliability, and camera stability. Although the dataset contains limitations—
such as selection bias, limited demographic information, and many short/emoji-only reviews—
the combined LDA and VADER approach still reveals valuable customer insights. These insights
can support Apple and retailers in enhancing user experience, strengthening customer satisfaction,
and guiding future product innovations.

本项目利用 Kaggle 的 iPhone 14 用户评论数据，通过 LDA 主题建模 和 VADER 情感分析，从消费者反馈中提取情绪倾向与主要关注主题，为产品设计、营销与客户体验提升提供洞察。

在清理数据后（移除非英文与无效文本），我们基于评论内容识别出四个核心主题：
相机性能、电池表现、品牌认知、配送服务。
然后将主题与情感评分结合，以了解用户对不同功能的态度。

分析结果显示：
相机性能与品牌相关评论整体偏正面
电池表现与配送相关评论负面比例较高
这揭示了 iPhone 14 的关键优势（品牌与相机）与主要改进点（电池续航和物流体验）。

尽管数据存在限制（如评论偏正面、缺少用户画像、部分内容过短或仅含表情符号），但 LDA+VADER 的双方法仍有效揭示了用户关注点与情绪趋势，为 Apple 提供了改善产品体验和优化服务流程的方向。

https://www.kaggle.com/datasets/shahriarkabir/iphone-14-customer-reviews-dataset-ratings
