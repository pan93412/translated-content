---
title: compositionupdate
slug: Web/API/Element/compositionupdate_event
translation_of: Web/API/Element/compositionupdate_event
original_slug: Web/Events/compositionupdate
---
L'événement **compositionupdate** est déclenché lorsqu'un caractère est ajouté à un passage de texte en train d'être composé (`démarre avec des caractères spéciaux qui nécessitent une sequence de touches et d'autres entrées telles que la reconnaissance vocale ou la suggestion de mots du mobile).`

## Informations générales

- Interface
  - : {{domxref("TouchEvent")}}
- Propagation
  - : Oui
- Annulable
  - : Non
- Cible
  - : {{domxref("Element")}}

## Propriétés

| Property                              | Type                                      | Description                                                                                |
| ------------------------------------- | ----------------------------------------- | ------------------------------------------------------------------------------------------ |
| `target` {{ReadOnlyInline}}     | {{domxref("EventTarget")}}      | Elément ayant le focus qui traite la composition. Nul si non-accessible.                   |
| `type` {{ReadOnlyInline}}       | {{domxref("DOMString")}}          | Le type de l'événement.                                                                    |
| `bubbles` {{ReadOnlyInline}}    | `boolean`                                 | Est-ce qu'il se propage?                                                                   |
| `cancelable` {{ReadOnlyInline}} | `boolean`                                 | Peut-il être annulé?                                                                       |
| `view` {{ReadOnlyInline}}       | {{domxref("WindowProxy")}}      | {{domxref("Document.defaultView")}} (fenêtre du document).                    |
| `detail` {{ReadOnlyInline}}     | `long` (`float`)                          | 0.                                                                                         |
| `data `{{ReadOnlyInline}}       | {{domxref("DOMString")}} (string) | La chaîne de caractères originale éditée ou une chaîne vide.                               |
| `locale `{{ReadOnlyInline}}     | {{domxref("DOMString")}} (string) | Le code de la langue pour l'événement de composition si disponible; Sinon une chaîne vide. |

## Compatibilités navigateur

{{Compat("api.Element.compositionupdate_event")}}

## Voir aussi

- {{Event("compositionstart")}}
- {{Event("compositionupdate")}}
- {{Event("compositionend")}}
