# conways-game-of-life

Scope of work

Core Game Features:
1. Basic Game Mechanics
- Conway's Game of Life rules engine
- Grid operations and state management
- SSE for live updates
- HTMX for frontend interactivity

2. Redis-based Session Management:
- Unique game sessions with TTL
- Game state persistence
- Session recovery/resume capability
- Background cleanup tasks for expired sessions
- Session statistics (active games, completed games)

3. Pattern Management API:
- REST endpoints for classic patterns (Glider, Blinker, etc.)
- Custom pattern creation and validation
- Pattern library with metadata
- Pattern transformation operations (rotate, scale)
- Pattern composition (combine multiple patterns)

4. Analysis Engine:
- Detect pattern types (still life, oscillator, spaceship)
- Calculate pattern statistics (growth rate, stability)
- Generation-by-generation analysis
- Performance metrics for different grid sizes

5. Advanced Features:
- Custom rule sets API (different survival/birth rules)
- Grid size adaptation
- Pattern optimization suggestions
- Boundary handling options (wrap-around vs finite)

Technical Implementation Goals:
1. Async Programming:
- Async views with Django
- Background tasks with Celery/APScheduler
- Redis pub/sub for real-time updates
- Async pattern analysis

2. Performance:
- Redis caching strategies
- Optimized grid computations
- Batch operations for large patterns
- Memory usage optimization

3. System Design:
- Clean architecture patterns
- Service layer abstraction
- Event-driven design
- Error handling and recovery
- Graceful degradation

4. Monitoring & Observability:
- Redis metrics tracking
- Performance monitoring
- Session analytics
- Error tracking and logging

This scope would give you practice with:
- Redis beyond basic caching
- Async Python
- System design patterns
- Performance optimization
- Real-time web features
- Clean API design

