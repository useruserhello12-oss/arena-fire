# Arena Fire 🔥

Un juego multijugador tipo Free Fire optimizado para dispositivos móviles, desarrollado en Unity.

## Características

### 🎮 Gameplay
- **Battle Royale** - 100 jugadores en tiempo real
- **Sistema de zonas** - Círculos dinámicos que se cierran
- **Loot system** - Armas, municiones, items de salud
- **Combate real** - Disparos, granadas, habilidades especiales

### 🌍 Mundo
- **Mapa dinámico** - Entorno destructible e interactivo
- **Sistema de eventos** - Misiones, desafíos durante la partida
- **Clima y efectos** - Lluvia, niebla, tormentas

### 👥 Multijugador
- **Conexión en tiempo real** - Photon PUN 2
- **Chat y comunicación** - Emojis, spray, pings
- **Sistema de equipos** - Solo, dúo, squad (3-4 jugadores)

### 📊 Progresión
- **Sistema de rangos** - Bronze, Plata, Oro, Platino, Diamante
- **Pase de batalla** - Recompensas semanales
- **Cosmética** - Skins, armas, emotes

### ⚡ Optimizado para móviles
- Controles táctiles intuitivos
- Bajo consumo de batería
- Gráficos escalables
- Sincronización eficiente de red

## Tech Stack

- **Engine**: Unity 2022 LTS
- **Networking**: Photon PUN 2
- **Backend**: Firebase + Custom Server
- **Database**: Firebase Realtime Database
- **Analytics**: Firebase Analytics

## Estructura del Proyecto

```
Assets/
├── Scripts/
│   ├── Core/              # Sistema principal del juego
│   ├── Networking/        # Sincronización multijugador
│   ├── UI/                # Interfaz de usuario
│   ├── Gameplay/          # Mecánicas de juego
│   ├── Player/            # Sistema de jugador
│   ├── Weapons/           # Armas y combate
│   ├── Map/               # Mapa y eventos
│   └── Managers/          # Managers globales
├── Prefabs/               # Prefabs de entidades
├── Scenes/                # Escenas del juego
├── Resources/             # Assets dinámicos
├── StreamingAssets/       # Datos estáticos
└── Settings/              # Configuraciones
```

## Instalación

1. Clonar el repositorio
```bash
git clone https://github.com/useruserhello12-oss/arena-fire.git
```

2. Abrir en Unity 2022 LTS o superior

3. Importar dependencias:
   - Photon PUN 2 (Asset Store)
   - TextMeshPro
   - Input System

4. Configurar credenciales de Firebase

5. Build para Android/iOS

## Roadmap

- [ ] Sistema base de jugador
- [ ] Mapa inicial (Isla Arena)
- [ ] Sistema de armas (20+ armas)
- [ ] Zona dinámica y círculo
- [ ] UI completa
- [ ] Sincronización multijugador
- [ ] Sistema de eventos y misiones
- [ ] Tienda y cosmética
- [ ] Rankings y estadísticas
- [ ] Beta testing

## License

MIT License

## Equipo

- Desarrollador: useruserhello12-oss
