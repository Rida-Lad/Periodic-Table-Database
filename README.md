# ⚗️ Periodic Table Database

A PostgreSQL database of chemical elements with a Bash interface for element lookup, created for freeCodeCamp's Relational Database certification.

## 📋 Project Overview
- **Database**: PostgreSQL
- **Interface**: Bash script
- **Features**:
  - Search elements by atomic number, symbol, or name
  - Display detailed element properties
  - Quick terminal-based access to periodic table data

## 📂 Required Files
| File | Purpose |
|------|---------|
| `periodic_table.sql` | Complete database dump of elements |
| `element.sh` | Interactive element lookup script |

## 🚀 Quick Setup
```bash
# 1. Clone the repository
git clone https://github.com/Rida-Lad/periodic-table-db.git
cd periodic-table-db

# 2. Import the database
psql -U postgres -f periodic_table.sql

# 3. Make the script executable
chmod +x element.sh

# 4. Run the application
./element.sh
```

## 📜 Certification
Part of freeCodeCamp's Relational Database Course

