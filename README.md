# iOS NLP : 자연어 처리
🍎 Apple CoreML ⚙️  
- CreateML로는 Text Generation을 할 수 없어서, CoreML을 활용하여 convert를 시도하였다.
- Pytorch SKT koGPT-2 modle -> coreML -> 용량 issue 🥲
- coreML 대신, OpenAI GPT-3 API와 Google MLKit Translate 기능을 활용하여 한국어 텍스트 생성 어플을 구현했다. 
- Textinit: https://github.com/SohyeonKim-dev/Textinit 
<img width="1624" alt="coreML NLP" src="https://user-images.githubusercontent.com/82718756/194762028-ae59eee3-6ca4-49b1-849f-a4eb29fd209b.png">
<img width="1624" alt="torch coreML" src="https://user-images.githubusercontent.com/82718756/194762018-ec4f1efe-17be-4aa0-b64f-d06eb5041958.png">
