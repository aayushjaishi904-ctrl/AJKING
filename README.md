# आयुस नेपाली साहित्य 🇳🇵

नेपाली कथा, कविता, निबन्ध, जीवनी, बाल साहित्य, रामायण र हनुमान चालिसाका लागि responsive static website.

## चलाउने तरिका
1. ZIP extract गर्नुहोस्।
2. `index.html` browser मा खोल्नुहोस्।
3. GitHub मा repository बनाएर सबै फाइल upload गर्नुहोस्।
4. Repository → Settings → Pages → Deploy from a branch → `main` / root छान्नुहोस्।

## फाइलहरू
- `index.html` — गृहपृष्ठ
- `katha.html`, `kabita.html`, `nibandha.html`, `jibani.html`
- `bal-sahitya.html`, `ramayan.html`, `hanuman-chalisa.html`
- `write.html` — पाठकको सिर्जना लेख्ने form
- `about.html` — मेरो बारेमा
- `assets/style.css` — design, border, responsive layout
- `assets/app.js` — search, theme, favorites, reading modal, local submission
- `assets/library.js` — नमुना सामग्री र विधा

## महत्त्वपूर्ण प्राविधिक कुरा
यो पहिलो static version हो। Form बाट लेखिएको सामग्री अहिले प्रयोगकर्ताको आफ्नै browser को localStorage मा मात्र सुरक्षित हुन्छ; वेबसाइटमा सार्वजनिक रूपमा प्रकाशित हुँदैन। सबै आगन्तुकका लागि साझा submission/publishing चाहियो भने Firebase/Supabase वा अन्य backend जोड्नुपर्छ।

अहिले हरेक विभागमा सुरुका नमुना सामग्री र विधा संरचना राखिएको छ। तपाईंले चाहनुभएको प्रत्येक विधामा १०० वटा लामो, गुणस्तरीय र तथ्य-जाँच गरिएका सामग्री एकैचोटि भरिएको छैन—त्यसका लागि छुट्टै चरणमा सामग्री विस्तार गर्नुपर्छ। रामायण/हनुमान चालिसाका पूर्ण पाठहरूका लागि प्रमाणित, उपयुक्त संस्करण प्रयोग गर्नुहोस्।
