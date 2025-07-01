# Play

## Fonction `Play`

la fonction `play` joue de l'audio, sous la forme de musique ou de sons.

Cf [jouer de l'audio](../../festures/audio.md) pour plus d'informations sur comment confifurer le système audio.

Syntaxe : `play [mode] [Nom] [canal (optionnel)]`

- mode : `music`, `ambiant` ou `sound`
- canal : a nombre désignant le canal utilisé. 0 par défault. Peut être utilisé pour jouer plusieurs musiques en parallèle sur le même mode.

## Exemple

```narrat
play music musicName 0
```