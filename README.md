<!--
BSD 3-Clause License

Copyright (c) 2025 Quux System and Technology. All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
   list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
-->

# Vanilla Mahjong (平和麻将)

Vanilla Mahjong is an experimental typography project that explores
representing Mahjong tiles as textual symbols.

Rather than treating Mahjong tiles as pictographic icons, emojis, or game UI
assets, this project approaches them as elements of a writing system. The focus
is on canonical tile forms, rule semantics, and Chinese-character-based
orthography, with typography as the primary design concern.

---

## Motivation

Unicode already defines a Mahjong tile block, and existing fonts such as the
Noto family provide baseline glyph coverage. However, these implementations
primarily target minimal correctness and fallback rendering, rather than
typographic integration.

Vanilla Mahjong explores an alternative direction:

- Mahjong treated as text rather than UI
- Tile faces expressed using Chinese characters
- Typographic consistency with CJK text
- Rule-aware presentation, including canonical color usage
- Semantic variation implemented via OpenType features instead of ad hoc glyph
  duplication

The intent is not to replace or redesign existing Mahjong glyphs, but to
construct a coherent typographic system around them.

---

## Scope (Planned)

This repository currently functions as a placeholder.

Planned work may include, but is not limited to:

- A Mahjong-dedicated font designed in alignment with CJK typographic
  conventions
- OpenType features for stylistic and semantic variants
- Support for canonical Chinese and Japanese Mahjong conventions
- Optional LaTeX tooling for textual Mahjong typesetting
- Documentation of typographic, orthographic, and design decisions

Implementation is expected to begin at a later stage.

---

## Design Principles

- Mahjong tile faces are written using Chinese characters.
- Auxiliary numeric, alphabetic, or Latin markings are treated as annotations
  and excluded.
- Unmarked and default forms are treated as the baseline.
- English terminology is used for explanation only and does not replace Mahjong
  orthography.

---

## Status

This project is currently in a dormant, pre-implementation phase.

The repository exists to reserve the project namespace and to document design
intent.  
Active development is expected to begin at a later time.

---

## License

The contents of this repository are released under the BSD 3-Clause License.

This repository currently contains design notes and documentation only.  
Font binaries, if published in the future, may be distributed under a different
license.

See the [LICENSE](LICENSE.md) file for details.

---

## Notes

The term “Vanilla” is used in the engineering sense:  
default, unadorned, and baseline, rather than simplified or decorative.

[modeline1]: # ( vim: set filetype=markdown noautoindent nojoinspaces: )
[modeline2]: # ( vim: set fileencoding=utf-8 spell spelllang=en: )
[modeline3]: # ( vim: set textwidth=78 tabstop=4 shiftwidth=4 softtabstop=4: )
