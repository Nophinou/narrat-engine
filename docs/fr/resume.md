# Resume

## Fonction `Resume`

La fonction `resume` reprend la lecture d'un canal audio.

Cf [jouer de l'audio](../../features.audio.md) pour plus d'informations sur comment configurer le système audio.

Syntaxe : `play [mode] [Nom] [canal (optionnel)]`

- mode : `music`, `ambiant` ou `sound`
- canal : a nombre désignant le canal utilisé. 0 par défault. Peut être utilisé pour jouer plusieurs musiques en parallèle sur le même mode.

## Exemple

```narrat
play music musicName
wait 3000
pause music
wait 200
resume music
```