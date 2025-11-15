# About Me
I enjoy using and translating FOSS.

Languages:
 - Simplified Chinese (zh_hans, zh_cn)
 - Traditional Chinese (zh_hant, zh_tw)
 - English (en, en_us)
 - Japanese (ja, ja_jp)

# Translation
 - +: Created translation
 - ↑: Updated translation (minor additions, string updates, or UI adjustments)
 - ⇧: Not the first translator, but handled a substantial portion of the translation

## Merged translations
| Project | Language | Notes |
| :--- | :--- | :--- |
| [Skyblocker](https://github.com/SkyblockerMod/Skyblocker) | ⇧zh_hans · ⇧zh_hant · ↑ja | Weblate |
| [Rush](https://github.com/shub39/Rush) | +zh_hans · +zh_hant · ↑ja | PR & Weblate |
| [Tooltip-Scroll-Fabric](https://github.com/Provismet/Tooltip-Scroll-Fabric) | +zh_hans · +zh_hant |
| [YetAnotherConfigLib](https://github.com/isXander/YetAnotherConfigLib) | ↑zh_hans |
| [LambDynamicLights](https://github.com/LambdAurora/LambDynamicLights) | ↑zh_hans · ↑zh_hant |
| [3d-Skin-Layers](https://github.com/tr7zw/3d-Skin-Layers) | ↑zh_hans · ↑zh_hant |
| [TipTapShow](https://github.com/Spyxar/TipTapShow) | +zh_hans · +zh_hant · +ja |
| [Dynamic-FPS](https://github.com/juliand665/Dynamic-FPS) | ↑zh_hans · ↑zh_hant |
| [mc-tcdcommons](https://github.com/TheCSMods/mc-tcdcommons) | ↑zh_hans · +zh_hant |
| [ProjectilesTrajectoryPreview](https://github.com/maDU59/ProjectilesTrajectoryPreview) | +zh_hans · +zh_hant · +ja |
| [chat_heads](https://github.com/dzwdz/chat_heads) | ↑zh_hans · ↑zh_hant · ↑ja |
| [gamma-utils](https://github.com/Sjouwer/gamma-utils) | ↑zh_hans · ↑zh_hant |

## Not merged yet
| Project | Language | Notes |
| :--- | :--- | :--- |
| [enchantinginfuser](https://github.com/Fuzss/enchantinginfuser) | ↑zh_hans · ↑zh_hant |  [See issuecomment](https://github.com/Fuzss/enchantinginfuser/pull/63#issuecomment-1902254937)|

## Weblate
See [Weblate](https://hosted.weblate.org/user/Anarkiisto/).

# FAQ
**Q: Why do you remove spaces between Chinese/Japanese characters and English letters or numbers?**

A: Spaces are not part of traditional Chinese or Japanese writing. In modern contexts, especially in computing and multilingual environments, spaces are sometimes used for visual purposes, but this is purely a formatting adjustment. Unlike Korean, Chinese and Japanese do not rely on spaces to indicate word boundaries, so spacing is not a feature of the language itself. Instead, character spacing should be handled by the typesetting engine.

Historically, people manually added spaces to improve layout, but modern solutions rely on automatic typesetting, which is considered best practice today. For web browsers, Chromium and Firefox both support text-autospace. In Minecraft, Mojang has been modernizing their game, and starting from version 1.20, this spacing issue has been resolved. Therefore, in most current rendering environments, adding spaces does not improve layout and may even cause inconsistencies.

**Q: Why do you sometimes only modify punctuation (such as replacing half-width characters with full-width characters) and grammar?**

A: Because these languages are meant to use their own punctuation marks. Using standardized punctuation is harmless and can improve the visual presentation of the text. It mainly requires the translator to pay more attention, but it benefits the product’s readability and appearance.

Sometimes, it is actually the half-width punctuation that requires special handling—for example, double quotes in JSON while full-width punctuation in normal text generally does not cause issues. Furthermore, users may have set different fonts for different languages. In such cases, non-standard symbols can lead to a poor visual experience.

In daily communication, speed is paramount, and strict grammatical precision is not essential; as long as it's understandable, it's sufficient, and even if not fully understood, it can be resolved through further discussion. However, software interfaces rely solely on the text itself and potentially nonexistent hints and documentation for comprehension. Therefore, adhering to language conventions is necessary.
