# Gold Price Widget 🇰🇷

📈 실시간 금값 (1g당 원화 환산)을 보여주는 깔끔한 위젯입니다.  
Vercel 또는 Netlify로 쉽게 배포해서 블로그나 웹사이트에 삽입할 수 있어요!

## 🔧 배포 방법
1. 이 템플릿을 GitHub에 fork
2. Netlify/Vercel에 연동
3. `<iframe>`으로 블로그에 삽입

```html
<iframe src="https://your-widget-url.netlify.app"
        width="100%" height="260" frameborder="0" scrolling="no"></iframe>
```

## 🔄 자동 갱신
5분마다 API로 자동 갱신됩니다.

## 📡 사용한 API
- Metals.live (https://api.metals.live/v1/spot/gold)
