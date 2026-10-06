# RTL / DOCX Technical Rules

Persian documents are primarily right-to-left.

At OOXML level use:
- `w:bidi`
- RTL paragraph properties
- `w:rtl` for relevant text runs
- Persian language metadata `fa-IR`
- complex-script font settings

Tables must be checked for RTL direction, cell paragraph direction, alignment, number placement and English abbreviations.

## Validation checklist
- [ ] Cover RTL
- [ ] Headings RTL
- [ ] Body RTL
- [ ] Persian language metadata
- [ ] Complex-script font settings
- [ ] English terms readable
- [ ] Numbers correctly positioned
- [ ] Tables stable
- [ ] Header/footer aligned
