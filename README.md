# Aku Jaga Diriku - Augmented Reality Child Personal Safety & Body Autonomy Education

![Unity Version](https://img.shields.io/badge/Unity-2022.3.62f3-blue.svg?style=for-the-badge&logo=unity)
![AR Framework](https://img.shields.io/badge/AR_SDK-PTC_Vuforia_Engine-orange.svg?style=for-the-badge)
![Audience](https://img.shields.io/badge/Target-Early_Childhood_(Ages_4--8)-pink.svg?style=for-the-badge)
![Pedagogy](https://img.shields.io/badge/Focus-Body_Autonomy_%26_Child_Protection-red.svg?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Android_APK-green.svg?style=for-the-badge&logo=android)

---

## 📖 1. Project Background & Child Protection Rationale

### 1.1 The Crucial Need for Early Body Safety Education
Child sexual abuse and boundary violations against young children (ages 4–8) frequently occur because children lack the developmental language and conceptual awareness to recognize inappropriate behavior. Perpetrators exploit this innocence through grooming, secrecy, or coercive authority.

Research in developmental psychology demonstrates that teaching children **body autonomy** and **body safety rules** significantly reduces vulnerability. However, discussing these topics can be uncomfortable for parents and educators without structured, age-appropriate educational materials.

### 1.2 The Aku Jaga Diriku Approach
**Aku Jaga Diriku** (*I Protect Myself*) is an Augmented Reality application created by early childhood education specialists to teach personal safety through a gentle, reassuring, non-fear-based approach.

Using child-friendly 3D character avatars and interactive storycards, children learn:
1. That their body is special and belongs solely to them.
2. The clear distinction between safe touches (affectionate, supportive touches) and unsafe touches.
3. The **Swimsuit Rule** designating the 4 private body parts that must never be touched or photographed by others.
4. The 3-step emergency action plan: **Say NO firmly, RUN to safety, and TELL a trusted adult immediately**.

---

## 🛡 2. 7-Stage Pedagogical Curriculum

| Curriculum Module | Scene File | Core Pedagogical Concepts & Child Safety Rules |
|:---|:---|:---|
| **Part 1: My Body Belongs to Me** | `Bagian1.unity` | Celebrating individuality and cultivating respect for personal physical boundaries. |
| **Part 2: Safe vs. Unsafe Touches** | `Bagian2.unity` | Differentiating warm, comfortable touches (family hugs, high-fives) from uncomfortable or confusing touches. |
| **Part 3: The Swimsuit Rule** | `Bagian3.unity` | Identifying the 4 private areas (mouth/lips, chest, genitals, and buttocks) that remain covered by swimwear and are strictly private. |
| **Part 4: Say NO with Conviction!** | `Bagian4.unity` | Empowering children to vocalize a firm, loud refusal (*"Jangan!"* or *"Tidak boleh!"*) without fear of getting in trouble. |
| **Part 5: Fleeing to Safety** | `Bagian5.unity` | Practical guidance on immediately running away from suspicious situations toward well-lit, crowded spaces. |
| **Part 6: Identifying Trusted Adults**| `Bagian6.unity` | Helping children map out their personal "Safety Network" (parents, school teachers, trusted grandparents). |
| **Part 7: Breaking Scary Secrets** | `Bagian7.unity` | Teaching children that unsafe secrets enforced by bribes or threats must always be shared with parents. |

---

## 📂 3. Directory Layout & Architecture
- **Main Unity Project:** `Aku Jaga Diriku/Aku Jaga Diriku/AkuJagaDiriku`
- **Core Scripts:** `LevelManager.cs` managing non-linear progression between curriculum segments.
- **Scenes:** `Start.unity`, `MainMenu.unity`, `AR.unity`, `Bagian1.unity` to `Bagian7.unity`, `Materi.unity`, `Petunjuk.unity`, `Tentang.unity`, `Pengembang.unity`.
