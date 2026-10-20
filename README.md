# Crazy Survival - Instancia Original

Instancia completa preconfigurada del servidor **Crazy Survival** (Paper 1.21.x) con soporte cross-play unificado para **Java** y **Bedrock**.

---

## 🌟 Características Integradas

- **Mundos:** `lobby`, `dungeon1`, `dungeon2`, `world`, `world_nether`, `world_the_end`.
- **Cross-Play Bedrock y Java:**
  - Soporte directo de Bedrock con `Geyser-Spigot` y `Floodgate`.
  - Motor de entidades y jefes 3D con `ModelEngine (v4.0.9)` y `GeyserModelEngine (v1.0.3)`.
  - Resource Pack de Bedrock (`CrazySurvival.mcpack`) preinstalado en `plugins/Geyser-Spigot/packs/` y en `bedrock_packs/`.
  - Mapeo de CustomModelData sincronizado (`custom_item_mappings.json`).
- **Texturas Java:**
  - Envío automático de texturas mediante `ForcePack` apuntando a `CrazySurvival.zip`.
- **Plugins:** Suite completa de economía, misiones, protecciones, habilidades (AuraSkills), tiendas y menús personalizados.

---

## 🚀 Puesta en Marcha

1. Asegúrate de tener **Java 21**.
2. Asigna permisos al ejecutable del servidor y arranca:
   ```bash
   java -Xms4G -Xmx6G -jar server.jar nogui
   ```
3. Los jugadores de Java recibirán automáticamente el Resource Pack al entrar.
4. Los jugadores de Bedrock recibirán `CrazySurvival.mcpack` con todos los modelos y texturas adaptados.
