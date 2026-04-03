# AI Workshop - OpenEdge ABL Project

This project demonstrates the ABL Business Entity Architecture Pattern for OpenEdge applications.

## Project Structure

- `src/business/` - Business Entity classes, Dataset definitions, and Entity Factory
- `src/*.w` - UI Windows (AppBuilder)
- `doc/` - Architecture documentation
- `dump/` - Database schema definitions
- `.windsurf/` - AI assistant rules and workflows

## Architecture

The project follows a layered architecture:
1. **UI Layer** - Windows/Forms (`.w` files)
2. **Factory Layer** - Singleton EntityFactory for entity lifecycle management
3. **Business Entity Layer** - Data access, validation, and business rules
4. **Dataset Layer** - Temp-table and ProDataSet definitions (`.i` files)

## Getting Started

1. Ensure OpenEdge 12.8+ is installed
2. Create the sports2000 database using `build.xml`
3. Open the project in Progress Developer Studio or compatible IDE
