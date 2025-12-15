<img width="1895" height="807" alt="image" src="https://github.com/user-attachments/assets/36a8d501-e4cf-40b7-928d-1905a88af8b8" />


# 🚀 API Hub - Modern Multi-API Dashboard
A beautiful, modern web application built with Flask that aggregates data from multiple APIs into one stunning, interactive dashboard. No database required for basic features - everything runs in your browser!



## 🎨 Design Highlights

- ✨ **Modern Glassmorphism UI** - Frosted-glass effect cards
- 🎨 **Purple Gradient Background** - Eye-catching aesthetic
- 💫 **Smooth Animations** - Fade-in effects and hover transitions
- 📱 **Fully Responsive** - Perfect on mobile, tablet, and desktop
- 🎯 **Intuitive Navigation** - Clean, easy-to-use interface
- ⚡ **Fast Loading** - Optimized for performance

---


## 🛠️ Technology Stack

### Backend
| Technology | Version | Purpose |
|------------|---------|---------|
| Flask | 3.0.0 | Web framework |
| Flask-SQLAlchemy | 3.1.1 | Database ORM |
| Flask-Migrate | 4.0.5 | Database migrations |
| Requests | 2.31.0 | HTTP library |
| Python-dotenv | 1.0.0 | Environment variables |

### Frontend
| Technology | Purpose |
|------------|---------|
| Bootstrap 5 | Responsive CSS framework |
| jQuery 3.7.1 | DOM manipulation & AJAX |
| Font Awesome 6.4 | Beautiful icons |
| Google Fonts (Poppins) | Modern typography |
| Custom CSS | Glassmorphism effects |

### APIs Integrated
| API | Cost | Usage Limit | Purpose |
|-----|------|-------------|---------|
| NewsAPI | FREE | 100 req/day | News articles from 90+ sources |
| OpenWeatherMap | FREE | 1,000 req/day | Weather data & forecasts |
| CoinGecko | FREE | Unlimited ✨ | Cryptocurrency prices |
| GitHub | FREE | 60 req/hour (5K with token) | Repository data |

---

## 🔒 Security
### Current Implementation
- ✅ **Environment Variables**: Sensitive data in `.env`
- ✅ **No API Keys in Frontend**: All keys server-side
- ✅ **CSRF Protection**: Flask-WTF enabled
- ✅ **SQL Injection Prevention**: SQLAlchemy ORM
- ✅ **XSS Protection**: Jinja2 auto-escaping



