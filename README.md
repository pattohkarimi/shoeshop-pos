# ShoeShop POS System

**Live Demo:** [Your Vercel URL will appear here after deployment]

## About
Inventory and sales management system for shoe retail with stock input capabilities.

## Features
- ✅ Role-based access (Admin/Worker)
- ✅ Real-time stock tracking by size (36-43) and color
- ✅ Sales recording with customer details & payment tracking
- ✅ **Stock Input Management** (Admin only)
  - New stock arrivals
  - Restock existing items
  - Adjust/correct inventory
  - Damage/loss recording
  - Bulk CSV upload
- ✅ Complete audit trail & stock history
- ✅ Analytics dashboard
- ✅ Data export (CSV)

## Initial Data (March 8, 2026 Arrivals)

### D1062 - Breathable Loafer ($5.80)
| Color | 36 | 37 | 38 | 39 | 40 | 41 | 42 | 43 | Total |
|-------|----|----|----|----|----|----|----|----|-------|
| Black | 1  | 3  | 7  | 8  | 8  | 7  | 6  | 5  | 45    |
| Grey  | 1  | 2  | 6  | 7  | 7  | 6  | 5  | 4  | 38    |
| Blue  | 1  | 2  | 6  | 7  | 7  | 6  | 5  | 4  | 38    |

### G1164 - Cross-Strap Sandals ($3.40)
| Color | 36 | 37 | 38 | 39 | 40 | 41 | 42 | 43 | Total |
|-------|----|----|----|----|----|----|----|----|-------|
| Black | 2  | 3  | 7  | 8  | 8  | 7  | 6  | 5  | 46    |
| Beige | 1  | 2  | 6  | 7  | 7  | 6  | 5  | 4  | 38    |
| Brown | 1  | 2  | 6  | 7  | 7  | 6  | 5  | 4  | 38    |

## Tech Stack
- Pure HTML/CSS/JavaScript (no frameworks needed)
- LocalStorage for data persistence
- Responsive design for mobile/tablet/desktop

## Deployment
Deployed on [Vercel](https://vercel.com) from GitHub repository.

## Access Levels
| Feature | Admin | Worker |
|---------|-------|--------|
| View Dashboard | ✅ | ✅ |
| Make Sales | ✅ | ✅ |
| View Inventory | ✅ | ✅ |
| **Stock Input/Management** | ✅ | ❌ |
| Delete Sales | ✅ | ❌ |
| View Analytics | ✅ | ❌ |
| Export Data | ✅ | ❌ |

## Default Login
- **Admin:** Administrator / Full Access
- **Workers:** John, Sarah, Mike / Sales Only

## Local Development
Simply open `index.html` in any modern browser. No server required.
