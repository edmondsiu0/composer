# composer
Wrapper script to perform bulk docker-compose up/down actions

## File Structure
```
.
├── composer
├── app1
│   ├── docker-compose.yaml
│   └── Dockerfile
├── app2
│   ├── docker-compose.yaml
│   └── Dockerfile
└── app3
    ├── docker-compose.yaml
    └── Dockerfile
```

## Usage
### Brining up all applications in directory
```bash
./composer all up
```

### Brining up `app2` only
```bash
./composer app2 up
```

### Brining down all applications in directory
```bash
./composer all down
```

### Brining down `app3` only
```bash
./composer app3 down
```
