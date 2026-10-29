# Wedding Invitation Content Update Specification

Status: FINALIZED

## Objective
Update the text content, dates, names, venues, and JavaScript configuration in the wedding invitation to match the new physical wedding card for Mohit & Sanjana (11 December 2026), without altering the royal styling, HTML structure, GSAP animations, Canvas petals, or Tone.js audio engine.

## Requirements

### 1. JavaScript Configuration
- `weddingDay`: "11"
- `weddingMonth`: "December"
- `weddingYear`: "2026"
- `receptionDate`: "10 December 2026"
- `calendarStartUTC`: "20261211T060000Z" (11 Dec 2026, 11:30 AM IST)
- `calendarEndUTC`: "20261211T140000Z" (11 Dec 2026, 7:30 PM IST)
- `calendarTitle`: "॥ शुभ विवाह ॥ मोहित संग संजना"
- `calendarLocation`: "Safdarjung Enclave & Sec-6, New Delhi"
- Update `calendarDetails` text with new details.
- Update `shareMessage` string in JS to reflect new names, dates, and venues.

### 2. Hero Section & Meta Title
- Change `<title>` and all instances of "रुद्र संग शांति" to "मोहित संग संजना" (Mohit & Sanjana).
- Change "रुद्र" to "मोहित" and "शांति" to "संजना".
- Change the date display text to "11 December 2026".

### 3. Invitation Message Section (मांगलिक परिणयोत्सव)
- Groom (वर): "चिरंजीवी मोहित"
- Groom's Parents: "सुपुत्र श्री सुबोध कुमार एवं श्रीमती सुमन" with subtext "(स्वर्गीय श्री चतरू राम एवं स्वर्गीय श्रीमती राम प्यारी के पौत्र)".
- Bride (वधू): "आयुष्मती संजना"
- Bride's Parents: "सुपुत्री श्री संजय राठौर एवं श्रीमती पुष्पा रानी".

### 4. Event Schedule Section (मांगलिक कार्यक्रम)
- Replace old June events with:
  1. "भात एवं लगन सगाई", Date: 10 December, Time: 5:00 PM, Details: "भात, लगन सगाई एवं डिनर"
  2. "घुड़चढ़ी", Date: 11 December, Time: 12:00 PM
  3. "बारात प्रस्थान", Date: 11 December, Time: 2:00 PM
- Update Venues with two cards:
  - Venue 1 (10 Dec): 18, डीडीए फ्लैट, सफदरजंग एन्क्लेव, नई दिल्ली - 110029
  - Venue 2 (11 Dec): सेक्टर-6, अमिटी इंटरनेशनल स्कूल के सामने, नई दिल्ली

### 5. Family & Well-Wishers Section
- Host Name: "श्री सुबोध कुमार एवं श्रीमती सुमन"
- Host Address: "19, डीडीए फ्लैट्स, सफदरजंग एन्क्लेव, नई दिल्ली - 110029"
- Phone Number: Single click-to-call button: `+91 9971668125`
- Well-Wishers Title: "R.S.V.P: समस्त खैराल परिवार" and "With Best Compliments From: समस्त संबंधी एवं मित्रगण"
- Kids Section (नन्हे दर्शनाभिलाषी): "गंगा, निवांश, रेहांश, चारी, ध्रुवी"

### 6. Footer Quote
- Keep poem intact; change family sign-off at bottom to "॥ खैराल परिवार ॥" (or "॥ सुबोध कुमार परिवार ॥").

### Files Targeted
- `index.html`
- `royal_indian_wedding_invitation_rudra_shanti.html`
