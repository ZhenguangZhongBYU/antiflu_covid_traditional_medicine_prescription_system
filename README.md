# 中医治感冒开方小程序 (Traditional Chinese Medicine Cold Prescription App)

## 介绍 (Introduction)
本小程序旨在通过分析用户的感冒症状，并结合中医理论，推荐最适合的中药材和剂量。用户根据实际症状进行评分，系统将自动计算并生成推荐的药方，帮助用户缓解感冒症状。

This app analyzes the user's cold symptoms and provides the most suitable Chinese herbs and dosages based on Traditional Chinese Medicine (TCM) theory. The user rates their symptoms, and the system calculates and generates a recommended prescription to help alleviate cold symptoms.

## 功能 (Features)
- **症状评分 (Symptom Rating)**：用户可以为不同的症状（如嗓子、胃肠、能量等）评分，系统根据评分推荐药方。
- **药材推荐 (Herb Recommendation)**：根据评分，系统推荐最合适的中药材和剂量。
- **中医理论讲解 (TCM Theory Explanation)**：提供感冒的中医理论分析，包括寒症、热症、胃肠症状等的辨证论治。

- **Symptom Rating**: Users can rate different symptoms (such as throat, gastrointestinal, energy levels), and the system will recommend prescriptions based on those ratings.
- **Herb Recommendation**: Based on ratings, the system recommends the most appropriate Chinese herbs and dosages.
- **TCM Theory Explanation**: Provides an explanation of Traditional Chinese Medicine theory on colds, including the differentiation of cold, heat, and gastrointestinal symptoms.

## 使用指南 (Usage Guide)

### 安装 (Installation)
1. 克隆此项目到本地：
    ```bash
    git clone https://github.com/yourusername/tcm-cold-prescription.git
    ```
2. 打开 `index.html` 文件，在浏览器中运行。

### 使用 (Usage)
1. 打开 `index.html` 文件。
2. 根据提示为每个症状评分（0到10分）。
3. 点击“计算推荐药方”按钮，查看系统推荐的中药材和剂量。

### Requirements
- 现代浏览器（Chrome, Firefox, Edge 等）

### 依赖 (Dependencies)
- 无 (No dependencies)

## 系统架构 (System Architecture)

本项目的架构如下：
- 前端：HTML、CSS、JavaScript (纯前端，无需后台)
- 算法：根据中医理论，依据症状评分计算推荐的药方
- 界面：简洁易用，响应式设计，支持各类设备

## 功能介绍 (Feature Overview)

1. **症状评分**：用户可以选择不同的症状，并对每个症状进行评分（0-10分），例如嗓子痛、胃肠不适、体力消耗等，系统将根据评分生成个性化药方推荐。
2. **药材推荐**：根据用户的症状评分，系统自动推荐相应的中药材及其剂量，并提供详细的使用说明。
3. **中医理论**：通过中医理论的讲解，帮助用户了解不同症状对应的中医病因，提供对症治疗的依据。

### 症状评分（Symptom Rating）

用户需要根据实际感冒症状，为不同症状（如嗓子、胃肠、能量等）进行评分。评分标准从0到10，0表示无症状，10表示最严重。

The user needs to rate different symptoms such as throat, gastrointestinal, and energy levels based on the actual cold symptoms. The rating scale is from 0 to 10, with 0 indicating no symptoms and 10 indicating the most severe symptoms.

### 药材推荐（Herb Recommendation）

根据用户的症状评分，系统将计算出最适合的中药材，并提供剂量推荐。例如，如果用户的嗓子痛评分较高，系统可能会推荐一些清热解毒、利咽止痛的药材。

Based on the user's symptom ratings, the system will calculate the most suitable herbs and provide dosage recommendations. For instance, if the user's throat pain score is high, the system might recommend herbs for clearing heat, detoxifying, and soothing the throat.

## 贡献 (Contributing)

欢迎您提交问题报告和拉取请求（Pull Requests），您的贡献将有助于我们改进此项目。

We welcome issue reports and pull requests (PRs) from you. Your contributions will help us improve this project.

1. Fork 该项目。
2. 创建您修改的分支。
3. 提交拉取请求。

## 许可证 (License)

此项目使用 MIT 许可证，详情请查看 LICENSE 文件。

This project is licensed under the MIT License. See the LICENSE file for more details.

## 联系我们 (Contact Us)

如有任何问题，请通过电子邮件联系我们：
- Email: example@example.com
