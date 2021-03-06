# Stringintelligenz
Gender-sensitive language for WordPress in German

**Stringintelligenz** is a feature project that aims to bring gender-sensitive language to German WordPress locales.

#### Case
German has three genders: masculine, feminine and neuter. Word endings often reveal grammatical gender—particularly for individuals, groups of individuals, job descriptions and the like:

```
der Benutzer      – the user – male, also used “generically”
ein Benutzer      – a user   – male, also used “generically”
die Benutzer      – users    – male, also used “generically”
die Benutzerin    – the user – female
eine Benutzerin   – a user   – female
die Benutzerinnen – users    – female
```

According to written German grammar, a “generic masculine” is meant to include individuals of all biological/social genders. However, studies have shown human perception does not understand a “generically” male gender as inclusive of other biological/social genders.

According to those studies, terms like `Benutzer` (user), `Entwickler` (developer), `Autor` (author), `Administrator` (administrator) and many others in WordPress will be intuitively understood primarily as male.

#### Example: generically applied captions

![German localization for “lead developer” implies Helen Hou-Sandí would be a male developer.](/screenshot-2.png)
_Helen gets captioned as a male developer in German._

A quite illustrative example is the caption `Leitender Entwickler` (Lead Developer, here: singular) on WordPress’ credits page. German translations clearly imply a **male individual** here. Yet that caption gets applied to each WordPress Lead Developer individually, including Helen Hou-Sandí who is a woman.

The appropriate caption for Helen would be `Leitende Entwicklerin` in German. In this particular case (like often times) we cannot apply proper grammatical gender to each Lead Developer individually due to technical restrictions.

#### Solutions: gender shortcuts
German offers several widely spread solutions to address this problem in written language:

- `Leitende/r Entwickler/in` (slash)
- `Leitende EntwicklerIn` (“Binnen-I”)
- `Leitende_r Entwickler_in` (“Gender Gap”)
- `Leitende*r Entwickler*in` (“Gender Star”)

All of these “gender suffixes” would be read and understood in the context of the individual they got applied to.

**Helen** would be understood as female:
```
Leitende Entwicklerin
```
while **Mark** would be understood as male:
```
Leitender Entwickler
```

**Plural forms** would be understood as both, female and male:
```
Leitende Entwickler*innen
```
would be read as lead developers (female and male):
```
Leitende Entwicklerinnen und leitende Entwickler
```

_**Note:** Gender scientists often recommend to try simplifying and “neutralizing” an expression first instead of using gender suffixes. In many cases phrasing can be adjusted to not rely on gender specific expressions._

#### Why WordPress? Why Now?
WordPress in German has over 3 million active installs. The potential impact of a gender-sensitive German UI for WordPress core could turn out as a significant contribution for the progress of gender-sensitive software interfaces in German in general.

Gender-sensitive language in core language packs could not only make WordPress in German more friendly and inclusive, it could potentially serve as a role model for other Polyglot communities from WordPress.org, as well as from other open source projects to implement their own solutions.

#### Roadmap

1. Draft a gender-sensitive translation for default German (`de_DE` locale, informal).
- Make draft available as a plugin on wordpress.org.
- Blog about it, e.g. on de.wordpress.org.
- Collect feedback via plugin forum on wordpress.org.
- Re-iterate, publish betas and Release Candidates.
- Transfer final RC into informal and formal `de_DE` core translations.
- Ship as default translations with a WordPress major release, for example with 4.7.
