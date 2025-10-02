# QSC Store Clone - Complete Documentation & Implementation Plan

## 📋 Table of Contents
1. [Crypto Wallet Addresses](#crypto-wallet-addresses)
2. [Contact Information](#contact-information)
3. [Store Structure](#store-structure)
4. [Product Categories](#product-categories)
5. [Checkout Process](#checkout-process)
6. [Payment Methods](#payment-methods)
7. [Technical Implementation](#technical-implementation)
8. [Cloning Steps](#cloning-steps)

---

## 💰 Crypto Wallet Addresses

### Current Sigma Audley Addresses:
```javascript
const wallets = {
    btc: 'bc1qhg472p650zyjzuuykv64c8srpjqjjxp7zyyz6p',          // Bitcoin (BTC Network)
    eth: '0xa8ba449Ff2A03e0Dd044076D4771D50Fb968a02B',          // Ethereum (ETH Network)
    pyusd: '0xa8ba449Ff2A03e0Dd044076D4771D50Fb968a02B',        // PayPal USD (ETH Network)
    xrp: 'rG7styHJw8t8b2AKYphtmu4yuUhUsXnjU2',                 // XRP (XRP Network)
    usdt: '0xa8ba449Ff2A03e0Dd044076D4771D50Fb968a02B',         // USDT (Ethereum Network)
    sol: '4wnct8Cwtov7seKiqd4ostndku6KGt7zjgaheVABXwKy',         // Solana (SOL Network)
    usdc: '0xa8ba449Ff2A03e0Dd044076D4771D50Fb968a02B',         // USDC (Ethereum Network)
    ada: 'addr1q9dcqk3593e2jqmj2j0206q6590m7m9n4xmdcdpl4cga6k6mspdrgtrj4yphy4y75l5p4g2lhakt82dkms6rlts3m4dsfy7y2w', // Cardano (ADA Network)
    bnb: '0xa8ba449Ff2A03e0Dd044076D4771D50Fb968a02B',          // BNB (BSC Network)
    ltc: 'LYjjaN9xmigYDddu5gj23HAaLjkFMDryBM',                  // Litecoin (LTC Network)
    tron: 'TC5FGoMTkeRkSitSFvdoG7vdnERNJjRGfL',                 // Tron (TRON Network)
    cbbtc: '0xa8ba449Ff2A03e0Dd044076D4771D50Fb968a02B'         // Coinbase Wrapped BTC (BASE Network)
};
```

### QR Codes Required:
- BTC QR CODE.png
- ETH QR CODE.png
- PYUSD ETH NETWORK QR CODE.png
- XRP QR CODE.png
- LTC QR CODE.png
- SOLANA QR CODE.png
- TETHER QR CODE.png
- USDC QR CODE.png
- CARDANO QR CODE.png
- BSC QR CODE.png
- TRON QR CODE.png
- CB QR CODE.png

---

## 📞 Contact Information

### Current Sigma Audley:
- **Email**: support@sigmaaudley.net
- **WhatsApp**: +852 54725263
- **Telegram**: No longer active
- **Website**: sigmaaudley.net

### For QSC Clone:
- **Email**: [Create new email like support@qsc.store]
- **WhatsApp**: [Use new business number]
- **Website**: [qsc.store or similar]

---

## 🏗️ Store Structure

### 1. **Header/Navigation**
- Logo
- Search bar (with advanced HGH/GH search functionality)
- Warehouse selector (US/EU/China)
- Currency selector (USD/EUR/GBP)
- Cart icon with count
- Mobile hamburger menu

### 2. **Hero Section**
- Promo banner with live countdown timer
- Discount tiers: 20% off $250+ | 30% off $500+ | 35% off $1000+ | 40% off $1500+ | 50% off $2500+
- Featured products notice: 20% OFF Featured Products
- Live operational status with date (updates daily Eastern Time)
- Email signup form

### 3. **Product Categories**
Main navigation with filtering:

#### Featured Products (~71 products)
- Filters: All | 💉 Peptides & Injectables | 💊 Steroids & SARMs

#### Weight Loss
- GLP-1 Agonists (Semaglutide, Tirzepatide, Retatrutide)
- Cagrilintide
- Combination products

#### Peptides
- Growth Hormones (HGH 6iu-36iu)
- Healing & Recovery (BPC-157, TB-500)
- Research Peptides
- NAD+ & Longevity
- Blends (GLOW50, GLOW70, etc.)

#### Oral Tablets
- Anabolic Steroids (Dianabol, Anavar, Winstrol, etc.)
- SARMs (RAD-140, MK-677, LGD-4033, etc.)
- Fat Burners (Clenbuterol)
- PCT Support (Tamoxifen, Clomid)

#### Injectables
- Testosterone variants
- Trenbolone
- Other steroids

### 4. **Product Display**
Each product card shows:
- Product image
- Name and specification
- Pricing tiers (base, 10-pack, 20-pack, 50-pack discounts)
- Janoshik lab test link
- Featured/Popular/Best Value badges
- Add to cart button
- Quick view modal

---

## 🛒 Checkout Process

### Step 1: Cart Review
- Product list with quantities
- Warehouse-based currency display
- Discount tier application
- Promo code input
- Total calculation

### Step 2: Warehouse Selection
- US Warehouse
- EU Warehouse
- China Warehouse (orders rerouted)

### Step 3: Shipping Information
- First Name, Last Name
- Email
- Street Address, City, State, ZIP
- Country

### Step 4: Payment Method Selection
1. **Crypto (12 options)**
   - Bitcoin, Ethereum, USDC, USDT
   - PayPal USD, Solana, XRP
   - Litecoin, Cardano, BNB
   - Tron, Coinbase Wrapped BTC

2. **Amazon Gift Card**
   - Step-by-step guide
   - Email: sigmaaudleypayment@gmail.com
   - Auto-calculation and instructions

3. **Bank Transfer/Wise**
   - Account details provided
   - Reference number system

4. **PayPal Goods & Services**
   - Email: sigmaaudleypayment@gmail.com
   - Fee calculation included

### Step 5: Payment Instructions
- QR code display for crypto
- Copy buttons for addresses/amounts
- Wallet information (Exodus, self-custody)
- Step-by-step crypto buying guides

### Step 6: Order Confirmation
- Order ID generation
- Email confirmation
- Order tracking info

---

## 💳 Payment Methods Detail

### Crypto Payment Flow:
1. User selects crypto option
2. System calculates amount based on live exchange rates
3. Display QR code + wallet address
4. Copy buttons for convenience
5. Confirmation after payment sent

### Amazon Gift Card Flow:
1. User buys gift card from Amazon
2. Sends to: sigmaaudleypayment@gmail.com
3. Email with order ID as subject
4. Manual verification

### Bank Transfer Flow:
1. Account details displayed
2. Reference: Order ID
3. Manual verification
4. Processing time: 1-3 days

---

## 🔧 Technical Implementation

### Core Technologies:
- **Frontend**: Pure HTML/CSS/JavaScript (no framework)
- **Styling**: Inline CSS + style blocks
- **Icons**: Font Awesome
- **Storage**: LocalStorage for cart/warehouse/currency
- **APIs**:
  - Exchange rates (live crypto pricing)
  - Google Analytics/Ads tracking

### Key Features:
1. **Live Currency Conversion**
   - Fetches exchange rates on page load
   - Updates every 5 minutes
   - Supports USD, EUR, GBP

2. **Search Functionality**
   - Enhanced HGH/GH search (matches "hgh", "gh", "somatropin", "growth hormone")
   - Searches: name, catalog number, specification, composition
   - Desktop + mobile versions
   - Dropdown with top 8 results

3. **Dynamic Pricing**
   - Quantity-based discounts
   - Order total discounts (tiers)
   - Featured product discounts
   - Promo code system

4. **Warehouse System**
   - US, EU, China options
   - Auto-currency switching
   - Shipping info per warehouse

5. **Cart Management**
   - LocalStorage persistence
   - Real-time updates
   - Quantity adjustments
   - Remove items

### File Structure:
```
/
├── index.html                 # Main store page
├── products/
│   ├── [product-slug].html   # Individual product pages
│   ├── peptides/index.html
│   └── growth-hormones/index.html
├── QR Code images/
│   ├── BTC QR CODE.png
│   ├── ETH QR CODE.png
│   └── [other crypto QR codes]
├── service-worker.js
├── sw.js
└── [SEO pages]
```

---

## 📝 Product Data Structure

### Featured Products (71 items):
Each product has:
```javascript
{
    "cat_no": "TR20-FEATURED",
    "name": "Tirzepatide",
    "specification": "20mg*10vials - 20% OFF!",
    "composition": "Dual GLP-1/GIP receptor agonist...",
    "janoshik_url": "https://janoshik.com/tests/...",
    "pricing": {
        "base": 66.4,
        "10": 56,
        "20": 53.6,
        "50": 50.4,
        "original": 83,
        "discount": 20
    },
    "category": "peptides",
    "subcategory": "weight_loss",
    "featured": true,
    "popular": true,
    "filter_type": "peptides-injectables"
}
```

### Categories:
- **featured_products**: 71 products (mixed)
- **weight_loss**: Semaglutide, Tirzepatide, Retatrutide variants
- **peptides**: HGH, healing, research, NAD+
- **oral_tablets**: Steroids, SARMs, PCT
- **injectables**: Injectable steroids

---

## 🚀 Cloning Steps for QSC

### Phase 1: Setup & Branding
1. **Domain & Hosting**
   - Register domain (e.g., qsc.store)
   - Set up hosting (Netlify/Vercel/GitHub Pages)

2. **Branding**
   - Create QSC logo
   - Replace all "Sigma Audley" mentions
   - Update color scheme if desired
   - Update contact info

3. **Crypto Wallets**
   - Generate new crypto addresses for all 12 currencies
   - Create QR codes for each
   - Update wallet object in code
   - Set up Exodus wallet for receiving

4. **Contact Setup**
   - Create support email (e.g., support@qsc.store)
   - Set up WhatsApp Business
   - Update all contact references

### Phase 2: Product Setup
1. **Copy Product Database**
   - Use existing product structure
   - Update Janoshik links (if different)
   - Adjust pricing if needed
   - Keep same catalog numbers or create new ones

2. **Images**
   - Copy QR code images
   - Update product images
   - Create favicon

3. **Featured Products**
   - 71 featured products already configured
   - Adjust discounts as needed
   - Update filter types

### Phase 3: Payment Integration
1. **Crypto Setup**
   - Test all 12 crypto payment flows
   - Verify QR codes work
   - Test copy buttons
   - Confirm wallet addresses

2. **Other Payments**
   - Set up Amazon gift card email
   - Configure bank transfer details
   - Set up PayPal email
   - Test Wise integration

### Phase 4: Technical Implementation
1. **Code Updates**
   - Find & replace "Sigma Audley" → "QSC"
   - Update email addresses
   - Update WhatsApp number
   - Update crypto wallet addresses
   - Update domain references

2. **Search Functionality**
   - Already enhanced for HGH/GH
   - Test all search terms
   - Verify dropdown works

3. **Live Features**
   - Date auto-update (Eastern Time)
   - Currency conversion
   - Exchange rate API
   - Promo timer

### Phase 5: Testing
1. **Functionality Tests**
   - Cart system
   - Warehouse switching
   - Currency conversion
   - Search
   - Checkout flow
   - All payment methods

2. **Mobile Responsiveness**
   - Test all screen sizes
   - Mobile search
   - Mobile checkout
   - Touch interactions

3. **Payment Tests**
   - Small test orders on each crypto
   - Verify QR codes scan correctly
   - Test copy functionality
   - Confirm wallet receipts

### Phase 6: Launch
1. **Pre-launch**
   - SSL certificate
   - Analytics setup (Google Analytics)
   - Error tracking
   - Backup strategy

2. **Go Live**
   - Deploy to production
   - Test live site
   - Monitor first orders
   - Customer support ready

3. **Marketing**
   - SEO optimization (copy Sigma Audley's SEO strategy)
   - Social media accounts
   - Reddit presence
   - Forum marketing

---

## 📊 Key Metrics to Track

1. **Orders**
   - Order volume
   - Average order value
   - Payment method distribution
   - Warehouse distribution

2. **Products**
   - Top sellers
   - Featured vs regular
   - Category performance
   - Search terms

3. **Conversion**
   - Cart abandonment rate
   - Checkout completion rate
   - Payment method success rate

---

## 🔐 Security Considerations

1. **Wallet Security**
   - Use hardware wallet for crypto storage
   - Regularly move funds to cold storage
   - Multi-sig for large amounts
   - Backup seed phrases securely

2. **Data Protection**
   - No customer data stored in code
   - Use LocalStorage only for cart
   - HTTPS everywhere
   - Privacy policy

3. **Payment Verification**
   - Manual verification for all orders
   - Check blockchain confirmations
   - Verify gift card codes
   - Bank transfer reference matching

---

## 📝 Additional Notes

### Warehouse Operations:
- **US**: Fast shipping, USD default
- **EU**: EUR currency, EU shipping
- **China**: Orders rerouted to US/EU

### Discount Tiers:
- $250+: 20% OFF
- $500+: 30% OFF
- $1000+: 35% OFF
- $1500+: 40% OFF
- $2500+: 50% OFF

### Featured Products Discount:
- Additional 20% OFF on top of quantity discounts

### Support Channels:
1. Primary: Email (support@qsc.store)
2. Secondary: WhatsApp
3. No longer: Telegram

---

## 🎯 Success Factors

1. **Trust Signals**
   - Janoshik lab tests for all products
   - Clear contact information
   - Professional design
   - Detailed product info

2. **User Experience**
   - Fast search
   - Easy checkout
   - Multiple payment options
   - Mobile-friendly

3. **Pricing Strategy**
   - Competitive base prices
   - Attractive bulk discounts
   - Clear savings display
   - Featured product deals

4. **Payment Flexibility**
   - 12 crypto options
   - Gift cards
   - Bank transfer
   - PayPal

---

## ✅ Launch Checklist

### Pre-Launch:
- [ ] Domain registered
- [ ] Hosting configured
- [ ] All crypto wallets generated
- [ ] QR codes created
- [ ] Contact email setup
- [ ] WhatsApp configured
- [ ] All branding updated
- [ ] Products imported
- [ ] Prices verified
- [ ] Payment methods tested

### Launch Day:
- [ ] Deploy to production
- [ ] Test live checkout
- [ ] Verify all crypto addresses
- [ ] Test email delivery
- [ ] Monitor first orders
- [ ] Customer support ready

### Post-Launch:
- [ ] SEO optimization
- [ ] Marketing campaigns
- [ ] Customer feedback collection
- [ ] Performance monitoring
- [ ] Regular security audits

---

## 📞 QSC Contact Template

**Customer Support Email:**
```
QSC Support Team
Email: support@qsc.store
WhatsApp: [Your Number]
Website: qsc.store

Operating Hours: 24/7
Response Time: Within 24 hours
```

---

## 🔄 Maintenance Schedule

**Daily:**
- Check new orders
- Verify payments
- Process shipments
- Answer support emails

**Weekly:**
- Update product inventory
- Review pricing
- Check crypto wallet balances
- Marketing campaigns

**Monthly:**
- Financial reports
- Product performance analysis
- Security audit
- Backup verification

---

## 📈 Growth Strategy

1. **Month 1-3**: Establish presence
   - Launch store
   - Build reputation
   - Gather reviews
   - Reddit/forum marketing

2. **Month 4-6**: Scale operations
   - Expand product line
   - Optimize conversions
   - Increase marketing
   - Partnership opportunities

3. **Month 7-12**: Dominate market
   - Market leader position
   - Premium brand status
   - Loyalty program
   - Wholesale options

---

*This document contains all necessary information to clone Sigma Audley store as QSC. Update wallet addresses, contact info, and branding before launch.*

**Last Updated:** October 2, 2025
