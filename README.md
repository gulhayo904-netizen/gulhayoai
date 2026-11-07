# gulhayo.ai — сайтлар

Master AI курси (ИИ-видео, шахсий бренд, Instagram’да ўсиш) учун сайтлар. Ҳар бир сайт битта HTML файл: HTML + CSS + JavaScript, сервер ёки йиғиш (build) керак эмас. Тил: ўзбекча (кирилл) ва русча, UZ/RU тугмаси билан.

## Тузилма

| Файл | Нима |
|---|---|
| `index.html` | Асосий сайт: парда очилади, скролл матога кириб боради, кадр-расмлар, 14 юлдузли ҳафта, FAQ (GSAP + ScrollTrigger) |
| `sites/3d-gulchambar/index.html` | Жонли осмон, мармар устун ва олтин гулчамбар 3D’да (Three.js) |
| `sites/3d-telefonlar/index.html` | Олтита йўналиш 3D телефонларда, уларнинг экранида Reels (Three.js) |
| `sites/kuch-energy-demo/index.html` | Демо: ўйлаб топилган KUCH энергетик бренди, 3D банкалар каруселида |

## Қандай очиш

Файлни браузерда очинг (икки марта босинг). Кутубхоналар (Three.js, GSAP) ва шрифтлар (Google Fonts) интернетдан юкланади.

## Расмларни алмаштириш

`index.html` даги расмлар ҳозир код билан чизилган. Ўзингизнинг ИИ-расмларингизни қўйиш учун файлдаги `window.PAINTINGS` қаторини топинг ва керакли жойга расм манзилини ёзинг:

```js
window.PAINTINGS={hero:'images/hero.jpg', macro:null, branch:null, lilac:null, night:null, parchment:null, grove:null, finale:null};
```

`null` турган жойда код билан чизилган расм қолади.

## Интернетга чиқариш (хоҳласангиз)

GitHub → **Settings → Pages** → Source: `Deploy from a branch`, Branch: `main`, папка `/ (root)`. Бир неча дақиқадан кейин сайт `https://gulhayo904-netizen.github.io/gulhayoai/` манзилида очилади. Ўз доменингизни (масалан, gulhayo.ai) ҳам шу ерда улаш мумкин.

## Ҳаволалар

Барча «Direct’га ёзиш» тугмалари `https://ig.me/m/gulhayo.ai` га олиб боради. Instagram: [@gulhayo.ai](https://www.instagram.com/gulhayo.ai/)
