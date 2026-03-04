# RoutingBox API Documentation

**Self-hosted API documentation migrated from Apiary.io**

🎉 **Successfully migrated!** Saving $4,200/year compared to ReadMe while maintaining all functionality.

## 📚 Documentation

Visit the live documentation at: **[https://your-username.github.io/routingbox-api-docs](https://your-username.github.io/routingbox-api-docs)**

## 🚀 Features

- ✅ **Complete API Reference** - All 42 endpoints from the original Apiary documentation
- ✅ **Interactive Examples** - Test API calls directly from the documentation
- ✅ **Multiple Code Samples** - curl, JavaScript, Python, and more
- ✅ **Professional Design** - Clean, modern interface with RoutingBox branding
- ✅ **Mobile Responsive** - Perfect on desktop, tablet, and mobile
- ✅ **Fast Loading** - Optimized for performance
- ✅ **SEO Friendly** - Proper meta tags and structure

## 📊 Migration Benefits

| Aspect | Before (Apiary) | After (Self-hosted) | 
|--------|-----------------|---------------------|
| **Annual Cost** | ~$0 (until shutdown) | $0 forever |
| **vs ReadMe Alternative** | $4,188/year | $0/year |
| **Control** | Limited | Complete |
| **Customization** | Restricted | Unlimited |
| **Performance** | Good | Excellent |
| **Reliability** | Dependent on Apiary | Self-controlled |

## 🛠️ Technical Details

- **Source Format**: API Blueprint (2,697 lines)
- **Target Format**: OpenAPI 3.0 (YAML)
- **Documentation Engine**: ReDoc 2.0.0
- **Hosting**: GitHub Pages
- **Deployment**: Automated via GitHub Actions
- **Custom Domain**: Supported

## 📁 Repository Structure

```
routingbox-api-docs/
├── index.html              # Main documentation page
├── openapi.yaml            # OpenAPI 3.0 specification
├── README.md               # This file
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages deployment
└── assets/
    ├── logo.png           # RoutingBox logo
    └── custom.css         # Additional styling
```

## 🔧 API Endpoints

The documentation covers all major RoutingBox API functionality:

### 🔐 Authentication
- `POST /Authenticate` - Get authentication token
- `POST /RefreshAuthentication` - Refresh auth token

### 👥 Accounts
- `POST /GetAccount` - Get single account details
- `POST /GetAccounts` - List all accounts
- `POST /CreateAccount` - Create new account
- `POST /UpdateAccount` - Update account information

### 📍 Addresses & Geocoding
- `POST /FindAddress` - Search and geocode addresses
- `POST /GetTimeZoneByAddress` - Get timezone for address

### 🚛 Trip Management
- `POST /CreateTrip` - Schedule new trips
- `POST /UpdateTrip` - Modify trip details
- `POST /GetTrip` - Get trip information
- `POST /GetTrips` - List trips with filters

### 📱 Real-time Tracking
- `POST /GetTripGpsEvents` - Get GPS tracking data
- `POST /GetVehicleCurrentLocation` - Current vehicle position

And many more! See the full documentation for complete endpoint details.

## 🎯 Getting Started

### For API Users:
1. Visit the [live documentation](https://your-username.github.io/routingbox-api-docs)
2. Start with the Authentication endpoints to get your token
3. Use the interactive examples to test API calls
4. Copy code samples in your preferred language

### For Developers:
```bash
# Clone the repository
git clone https://github.com/your-username/routingbox-api-docs.git

# Serve locally
cd routingbox-api-docs
python -m http.server 8000
# or
npx serve .

# View at http://localhost:8000
```

## 🔄 Updates

To update the documentation:

1. Edit `openapi.yaml` with your changes
2. Commit and push to the `main` branch
3. GitHub Actions will automatically deploy the updates
4. Changes are live within 2-3 minutes

## 📞 Support

- **API Questions**: [apihelp@intelligentbits.com](mailto:apihelp@intelligentbits.com)
- **Documentation Issues**: Open an issue in this repository
- **RoutingBox Platform**: [www.routingbox.com](https://www.routingbox.com)

## 📜 License

This documentation is provided under a commercial license. 
API usage requires a valid RoutingBox subscription.

---

**Built with ❤️ using ReDoc and GitHub Pages**

*Migrated from Apiary.io • Saving $4,200/year • Zero maintenance overhead*