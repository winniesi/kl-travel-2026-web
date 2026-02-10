# KL Travel Guide 2026 - Design Specification

## 1. Theme & Branding
- **Color Palette**: Dark Slate (#0f172a), Gold (#d4af37), White (#f8fafc).
- **Style**: Modern, premium, mobile-first. Use glassmorphism (backdrop-blur) for content cards.

## 2. Location Data & descriptions (Bilingual)

### Stop 0: KLIA Terminal (吉隆坡国际机场)
- **Why**: Entry point. Fast-track immigration for T1.
- **Maps**: `comgooglemaps://?q=KLIA`, `http://maps.apple.com/?q=KLIA`
- **Next**: Luna Hotel (55km, RM 65-85, 50m)

### Stop 1: Luna Hotel (莱恩酒店)
- **Why**: Your base. Drop off luggage at 4:50 AM to start the day light.
- **Maps**: `comgooglemaps://?q=Luna+Hotel+KL`, `http://maps.apple.com/?q=Luna+Hotel+KL`
- **Next**: ICC Pudu (1.2km, RM 5, 5m or walk 15m)

### Stop 2: ICC Pudu (早餐圣地)
- **Why**: "吉隆坡早餐之魂"。必吃：阿荣哥海南茶，燕美姜酒米粉。凌晨6点最有烟火气。
- **Maps**: `comgooglemaps://?q=ICC+Pudu`, `http://maps.apple.com/?q=ICC+Pudu`
- **Next**: Kwai Chai Hong (2km, RM 7, 8m)

### Stop 3: Kwai Chai Hong (鬼仔巷)
- **Why**: 错峰拍摄。清晨没有游客，光影映在壁画上最出片。
- **Maps**: `comgooglemaps://?q=Kwai+Chai+Hong`, `http://maps.apple.com/?q=Kwai+Chai+Hong`
- **Next**: VCR Coffee (1.5km, RM 6, 6m)

### Stop 4: VCR Coffee (精品咖啡)
- **Why**: 这里的精品咖啡和 Avocoda Toast 能把你从红眼航班的疲惫中彻底唤醒。
- **Maps**: `comgooglemaps://?q=VCR+Jalan+Galloway`, `http://maps.apple.com/?q=VCR+Jalan+Galloway`

### Stop 5: KLCC / Petronas Towers (双子塔)
- **Why**: 必打卡地标。去 Kinokuniya 书店避暑，或在中央公园拍水池倒影。
- **Maps**: `comgooglemaps://?q=KLCC`, `http://maps.apple.com/?q=KLCC`

### Stop 6: Madam Kwan's (关姐厨房)
- **Why**: 最稳的椰浆饭 (Nasi Lemak)。环境好，适合中午体面休息。
- **Maps**: `comgooglemaps://?q=Madam+Kwans+KLCC`, `http://maps.apple.com/?q=Madam+Kwans+KLCC`

### Stop 7: Liang Xin (良心按摩)
- **Why**: 特种兵续命点。下午2点最困时，来一次正宗足疗或推拿。
- **Maps**: `comgooglemaps://?q=Liang+Xin+Massage+KL`, `http://maps.apple.com/?q=Liang+Xin+Massage+KL`

### Stop 8: Heli Lounge Bar (直升机停机坪)
- **Why**: 360°无遮挡日落。在没有任何护栏的停机坪上看全世界。注意长裤/包鞋。
- **Maps**: `comgooglemaps://?q=Heli+Lounge+Bar`, `http://maps.apple.com/?q=Heli+Lounge+Bar`

### Stop 9: Jalan Alor / Wong Ah Wah (黄亚华)
- **Why**: 阿罗街的尽头。烧鸡翅、福建面必点。用最热辣的街头美食结束一天。
- **Maps**: `comgooglemaps://?q=Wong+Ah+Wah+Jalan+Alor`, `http://maps.apple.com/?q=Wong+Ah+Wah+Jalan+Alor`

## 3. UI Requirements
- Vertical Timeline with icons.
- High-res images from stable sources (Unsplash ID explicit).
- Distance & Cost badges for each segment.
- Interactive deep-link buttons.
