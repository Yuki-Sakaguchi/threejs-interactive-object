# Three.js interractive object

Three.jsを使ってユーザーの操作に応じたアニメーションを実装してみる。  

- ユーザーのスクロールに応じたアニメーション
- NormalMapをテクスチャとして使用
- スポットライトを2つ配置して色を演出
  - dat.guiによるスポットライトの位置調整、色味調整
  - PointLightHelperによるスポットライトのチェック
- canvasをcssのmix-blend-mode: exclusionを使うことでDOMと重なった時の演出を調整


## Setup
Download [Node.js](https://nodejs.org/en/download/).
Run this followed commands:

``` bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```

# 参考

- https://www.youtube.com/watch?v=pUgWfqWZWmM
- https://github.com/designcourse/threejs-webpack-starter
- https://threejs-journey.xyz/