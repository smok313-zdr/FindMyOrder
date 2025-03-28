# FindMyOrder

### Wprowadzenie

FindMyOrder to aplikacja identyfikująca baretki Wojska Polskiego po zdjęciu wykorzystując do tego celu Konwolucyjne Sieci Neuronowe (CNN). Do procesu nauki Sieci Neuronowej wykorzystano obrazy odpowiednich beretek z internetu oraz z mundurów żołnierzy Wojska Polskiego. Do poprawienia jakości predykcji nowych zdjęć, zastosowano warstwę dropout (`keras.layers.Dropout`) jako technikę regularyzacji, która pomaga zapogiebać nadmiernemu dopasowaniu. Aplikacja jest w stanie rozpoznać nawet przyciemnione lub lekko wyblakłe baretki. Skuteczność predykcji wynosi około 99%.       

