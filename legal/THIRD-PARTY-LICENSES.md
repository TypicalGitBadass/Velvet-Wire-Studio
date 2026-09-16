# Third-Party Licenses

Generated from the locked production dependency graph. Remotion-specific scanner exceptions are resolved against the installed 4.0.507 package manifests and shipped license files.

## Remotion 4.0.507 license resolution

| Package | Relationship | Package metadata / local evidence | Classification |
|---|---|---|---|
| `@remotion/bundler` 4.0.507 | Direct production dependency; packaged | Remotion License (package LICENSE.md, explicit metadata, or Remotion monorepo inheritance) | SPECIAL LICENSE - DOCUMENTED |
| `@remotion/captions` 4.0.507 | Transitive production dependency; packaged | MIT package metadata; MIT notice reproduced below | CLEAR WITH NOTICE |
| `@remotion/compositor-win32-x64-msvc` 4.0.507 | Transitive production dependency; packaged | Remotion License (package LICENSE.md, explicit metadata, or Remotion monorepo inheritance) | SPECIAL LICENSE - DOCUMENTED |
| `@remotion/licensing` 4.0.507 | Transitive production dependency; packaged | MIT package metadata; MIT notice reproduced below | CLEAR WITH NOTICE |
| `@remotion/media-parser` 4.0.507 | Transitive production dependency; packaged | Remotion License (package LICENSE.md, explicit metadata, or Remotion monorepo inheritance) | SPECIAL LICENSE - DOCUMENTED |
| `@remotion/media-utils` 4.0.507 | Transitive production dependency; packaged | MIT package metadata; MIT notice reproduced below | CLEAR WITH NOTICE |
| `@remotion/player` 4.0.507 | Direct production dependency; packaged | Remotion License (package LICENSE.md, explicit metadata, or Remotion monorepo inheritance) | SPECIAL LICENSE - DOCUMENTED |
| `@remotion/renderer` 4.0.507 | Direct production dependency; packaged | Remotion License (package LICENSE.md, explicit metadata, or Remotion monorepo inheritance) | SPECIAL LICENSE - DOCUMENTED |
| `@remotion/streaming` 4.0.507 | Transitive production dependency; packaged | MIT package metadata; MIT notice reproduced below | CLEAR WITH NOTICE |
| `@remotion/studio` 4.0.507 | Transitive production dependency; packaged | MIT package metadata; MIT notice reproduced below | CLEAR WITH NOTICE |
| `@remotion/studio-protocol` 4.0.507 | Transitive production dependency; packaged | Remotion License (package LICENSE.md, explicit metadata, or Remotion monorepo inheritance) | SPECIAL LICENSE - DOCUMENTED |
| `@remotion/studio-shared` 4.0.507 | Transitive production dependency; packaged | MIT package metadata; MIT notice reproduced below | CLEAR WITH NOTICE |
| `@remotion/timeline-utils` 4.0.507 | Transitive production dependency; packaged | MIT package metadata; MIT notice reproduced below | CLEAR WITH NOTICE |
| `@remotion/web-renderer` 4.0.507 | Transitive production dependency; packaged | Remotion License (package LICENSE.md, explicit metadata, or Remotion monorepo inheritance) | SPECIAL LICENSE - DOCUMENTED |
| `@remotion/zod-types` 4.0.507 | Transitive production dependency; packaged | MIT package metadata; MIT notice reproduced below | CLEAR WITH NOTICE |
| `remotion` 4.0.507 | Direct production dependency; packaged | Remotion License (package LICENSE.md, explicit metadata, or Remotion monorepo inheritance) | SPECIAL LICENSE - DOCUMENTED |

The previous six `Unknown` labels were scanner limitations: five manifests use `SEE LICENSE IN LICENSE.md`, and the Windows compositor package omits a license field while identifying the Remotion monorepo as its source. The two explicit `Remotion License` labels use the same special-license family. All eight are documented here under the Remotion License; none is represented as MIT.

### Remotion License text bundled with 4.0.507

```text
# Remotion License

In Remotion 5.0, the license will slightly change. [View the changes here](https://github.com/remotion-dev/remotion/pull/3750).

---

Depending on the type of your legal entity, you are granted permission to use Remotion for your project. Individuals and small companies are allowed to use Remotion to create videos for free (even commercial), while a company license is required for for-profit organizations of a certain size. This two-tier system was designed to ensure funding for this project while still allowing the source code to be available and the program to be free for most. Read below for the exact terms of use.

- [Free License](#free-license)
- [Company License](#company-license)

## Free License

Copyright © 2026 [Remotion](https://www.remotion.dev)

### Eligibility

You are eligible to use Remotion for free if you are:

- an individual
- a for-profit organization with up to 3 employees
- a non-profit or not-for-profit organization
- evaluating whether Remotion is a good fit, and are not yet using it in a commercial way

### Allowed use cases

Permission is hereby granted, free of charge, to any person eligible for the "Free License", to use the software non-commercially or commercially for the purpose of creating videos and images and to modify the software to their own liking, for the purpose of fulfilling their custom use case or to contribute bug fixes or improvements back to Remotion.

### Disallowed use cases

It is not allowed to copy or modify Remotion code for the purpose of selling, renting, licensing, relicensing, or sublicensing your own derivate of Remotion.

### Warranty notice

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the author or copyright holders be liable for any claim, damages or other liability, whether in an action of contract, tort or otherwise, arising from, out of or in connection with the software or the use or other dealings in the software.

### Support

Support is provided on a best-we-can-do basis via GitHub Issues and Discord.

## Company License

You are required to obtain a Company License to use Remotion if you are not within the group of entities eligible for a Free License. This license will enable you to use Remotion for the allowed use cases specified in the Free License, and give you access to prioritized support (read the [Support Policy](https://www.remotion.dev/docs/support)).

Visit [remotion.pro](https://www.remotion.pro/license) for pricing and to buy a license.

### FAQs

Are you not sure whether you need a Company License because of an edge case? Here are some [frequently asked questions](https://www.remotion.pro/faq).
```

### MIT notice for the eight MIT-identified Remotion packages

```text
Copyright (c) 2021 JonnyBurger

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

## Velvet Wire controlled FFmpeg renderer runtime

Velvet Wire Studio ships a Windows x64 FFmpeg 7.1 runtime built from the exact corresponding-source archives included at `resources/renderer-source`. The build enables GPL and links x264 commit `b35605ace3ddf7c1a5d67a2eb553f034aef41d55` plus zlib 1.3.2. It does not enable libfdk-aac, x265, or FFmpeg's nonfree option. AAC export uses FFmpeg's native AAC encoder.

| Component | Exact source | License |
|---|---|---|
| FFmpeg 7.1 | `renderer-source/ffmpeg-7.1.tar.xz` (SHA-256 `40973D44970DBC83EF302B0609F2E74982BE2D85916DD2EE7472D30678A7ABE6`) | GNU GPL version 2 or later for this configured build |
| x264 commit `b35605ace3ddf7c1a5d67a2eb553f034aef41d55` | `renderer-source/x264-b35605ace3ddf7c1a5d67a2eb553f034aef41d55.tar.gz` (SHA-256 `CD71A7515B0E9A012E1AC9B1F8415BEBCAF6FC97D4DB32286642AC4C0FBE24F9`) | GNU GPL version 2 or later |
| zlib 1.3.2 | `renderer-source/zlib-1.3.2.tar.gz` (SHA-256 `BB329A0A2CD0274D05519D61C667C062E06990D72E125EE2DFA8DE64F0119D16`) | zlib License |
| Velvet Wire native-AAC launcher | `renderer-source/ffmpeg-native-aac-launcher.c` | Copyright (C) 2026 TypicalNoctis. All rights reserved. Separate process launcher; not linked with FFmpeg. |

The exact reproducible build script is `renderer-source/build-ffmpeg-windows-x64.sh`. `renderer-source/README.md` records the toolchain, build inputs, binary inventory, and source locations. No source patches are applied to FFmpeg, x264, zlib, or Remotion.

x264 is Copyright (C) 2003-2025 the x264 project. Its source states that it may be redistributed and/or modified under GNU GPL version 2 or, at the recipient's option, any later version. The exact source archive includes `AUTHORS`, `COPYING`, and the source-file notices.

### GNU General Public License version 2

The following complete text applies to the GPL renderer components described above.

```text
GNU GENERAL PUBLIC LICENSE
                       Version 2, June 1991

 Copyright (C) 1989, 1991 Free Software Foundation, Inc.,
 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The licenses for most software are designed to take away your
freedom to share and change it.  By contrast, the GNU General Public
License is intended to guarantee your freedom to share and change free
software--to make sure the software is free for all its users.  This
General Public License applies to most of the Free Software
Foundation's software and to any other program whose authors commit to
using it.  (Some other Free Software Foundation software is covered by
the GNU Lesser General Public License instead.)  You can apply it to
your programs, too.

  When we speak of free software, we are referring to freedom, not
price.  Our General Public Licenses are designed to make sure that you
have the freedom to distribute copies of free software (and charge for
this service if you wish), that you receive source code or can get it
if you want it, that you can change the software or use pieces of it
in new free programs; and that you know you can do these things.

  To protect your rights, we need to make restrictions that forbid
anyone to deny you these rights or to ask you to surrender the rights.
These restrictions translate to certain responsibilities for you if you
distribute copies of the software, or if you modify it.

  For example, if you distribute copies of such a program, whether
gratis or for a fee, you must give the recipients all the rights that
you have.  You must make sure that they, too, receive or can get the
source code.  And you must show them these terms so they know their
rights.

  We protect your rights with two steps: (1) copyright the software, and
(2) offer you this license which gives you legal permission to copy,
distribute and/or modify the software.

  Also, for each author's protection and ours, we want to make certain
that everyone understands that there is no warranty for this free
software.  If the software is modified by someone else and passed on, we
want its recipients to know that what they have is not the original, so
that any problems introduced by others will not reflect on the original
authors' reputations.

  Finally, any free program is threatened constantly by software
patents.  We wish to avoid the danger that redistributors of a free
program will individually obtain patent licenses, in effect making the
program proprietary.  To prevent this, we have made it clear that any
patent must be licensed for everyone's free use or not licensed at all.

  The precise terms and conditions for copying, distribution and
modification follow.

                    GNU GENERAL PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. This License applies to any program or other work which contains
a notice placed by the copyright holder saying it may be distributed
under the terms of this General Public License.  The "Program", below,
refers to any such program or work, and a "work based on the Program"
means either the Program or any derivative work under copyright law:
that is to say, a work containing the Program or a portion of it,
either verbatim or with modifications and/or translated into another
language.  (Hereinafter, translation is included without limitation in
the term "modification".)  Each licensee is addressed as "you".

Activities other than copying, distribution and modification are not
covered by this License; they are outside its scope.  The act of
running the Program is not restricted, and the output from the Program
is covered only if its contents constitute a work based on the
Program (independent of having been made by running the Program).
Whether that is true depends on what the Program does.

  1. You may copy and distribute verbatim copies of the Program's
source code as you receive it, in any medium, provided that you
conspicuously and appropriately publish on each copy an appropriate
copyright notice and disclaimer of warranty; keep intact all the
notices that refer to this License and to the absence of any warranty;
and give any other recipients of the Program a copy of this License
along with the Program.

You may charge a fee for the physical act of transferring a copy, and
you may at your option offer warranty protection in exchange for a fee.

  2. You may modify your copy or copies of the Program or any portion
of it, thus forming a work based on the Program, and copy and
distribute such modifications or work under the terms of Section 1
above, provided that you also meet all of these conditions:

    a) You must cause the modified files to carry prominent notices
    stating that you changed the files and the date of any change.

    b) You must cause any work that you distribute or publish, that in
    whole or in part contains or is derived from the Program or any
    part thereof, to be licensed as a whole at no charge to all third
    parties under the terms of this License.

    c) If the modified program normally reads commands interactively
    when run, you must cause it, when started running for such
    interactive use in the most ordinary way, to print or display an
    announcement including an appropriate copyright notice and a
    notice that there is no warranty (or else, saying that you provide
    a warranty) and that users may redistribute the program under
    these conditions, and telling the user how to view a copy of this
    License.  (Exception: if the Program itself is interactive but
    does not normally print such an announcement, your work based on
    the Program is not required to print an announcement.)

These requirements apply to the modified work as a whole.  If
identifiable sections of that work are not derived from the Program,
and can be reasonably considered independent and separate works in
themselves, then this License, and its terms, do not apply to those
sections when you distribute them as separate works.  But when you
distribute the same sections as part of a whole which is a work based
on the Program, the distribution of the whole must be on the terms of
this License, whose permissions for other licensees extend to the
entire whole, and thus to each and every part regardless of who wrote it.

Thus, it is not the intent of this section to claim rights or contest
your rights to work written entirely by you; rather, the intent is to
exercise the right to control the distribution of derivative or
collective works based on the Program.

In addition, mere aggregation of another work not based on the Program
with the Program (or with a work based on the Program) on a volume of
a storage or distribution medium does not bring the other work under
the scope of this License.

  3. You may copy and distribute the Program (or a work based on it,
under Section 2) in object code or executable form under the terms of
Sections 1 and 2 above provided that you also do one of the following:

    a) Accompany it with the complete corresponding machine-readable
    source code, which must be distributed under the terms of Sections
    1 and 2 above on a medium customarily used for software interchange; or,

    b) Accompany it with a written offer, valid for at least three
    years, to give any third party, for a charge no more than your
    cost of physically performing source distribution, a complete
    machine-readable copy of the corresponding source code, to be
    distributed under the terms of Sections 1 and 2 above on a medium
    customarily used for software interchange; or,

    c) Accompany it with the information you received as to the offer
    to distribute corresponding source code.  (This alternative is
    allowed only for noncommercial distribution and only if you
    received the program in object code or executable form with such
    an offer, in accord with Subsection b above.)

The source code for a work means the preferred form of the work for
making modifications to it.  For an executable work, complete source
code means all the source code for all modules it contains, plus any
associated interface definition files, plus the scripts used to
control compilation and installation of the executable.  However, as a
special exception, the source code distributed need not include
anything that is normally distributed (in either source or binary
form) with the major components (compiler, kernel, and so on) of the
operating system on which the executable runs, unless that component
itself accompanies the executable.

If distribution of executable or object code is made by offering
access to copy from a designated place, then offering equivalent
access to copy the source code from the same place counts as
distribution of the source code, even though third parties are not
compelled to copy the source along with the object code.

  4. You may not copy, modify, sublicense, or distribute the Program
except as expressly provided under this License.  Any attempt
otherwise to copy, modify, sublicense or distribute the Program is
void, and will automatically terminate your rights under this License.
However, parties who have received copies, or rights, from you under
this License will not have their licenses terminated so long as such
parties remain in full compliance.

  5. You are not required to accept this License, since you have not
signed it.  However, nothing else grants you permission to modify or
distribute the Program or its derivative works.  These actions are
prohibited by law if you do not accept this License.  Therefore, by
modifying or distributing the Program (or any work based on the
Program), you indicate your acceptance of this License to do so, and
all its terms and conditions for copying, distributing or modifying
the Program or works based on it.

  6. Each time you redistribute the Program (or any work based on the
Program), the recipient automatically receives a license from the
original licensor to copy, distribute or modify the Program subject to
these terms and conditions.  You may not impose any further
restrictions on the recipients' exercise of the rights granted herein.
You are not responsible for enforcing compliance by third parties to
this License.

  7. If, as a consequence of a court judgment or allegation of patent
infringement or for any other reason (not limited to patent issues),
conditions are imposed on you (whether by court order, agreement or
otherwise) that contradict the conditions of this License, they do not
excuse you from the conditions of this License.  If you cannot
distribute so as to satisfy simultaneously your obligations under this
License and any other pertinent obligations, then as a consequence you
may not distribute the Program at all.  For example, if a patent
license would not permit royalty-free redistribution of the Program by
all those who receive copies directly or indirectly through you, then
the only way you could satisfy both it and this License would be to
refrain entirely from distribution of the Program.

If any portion of this section is held invalid or unenforceable under
any particular circumstance, the balance of the section is intended to
apply and the section as a whole is intended to apply in other
circumstances.

It is not the purpose of this section to induce you to infringe any
patents or other property right claims or to contest validity of any
such claims; this section has the sole purpose of protecting the
integrity of the free software distribution system, which is
implemented by public license practices.  Many people have made
generous contributions to the wide range of software distributed
through that system in reliance on consistent application of that
system; it is up to the author/donor to decide if he or she is willing
to distribute software through any other system and a licensee cannot
impose that choice.

This section is intended to make thoroughly clear what is believed to
be a consequence of the rest of this License.

  8. If the distribution and/or use of the Program is restricted in
certain countries either by patents or by copyrighted interfaces, the
original copyright holder who places the Program under this License
may add an explicit geographical distribution limitation excluding
those countries, so that distribution is permitted only in or among
countries not thus excluded.  In such case, this License incorporates
the limitation as if written in the body of this License.

  9. The Free Software Foundation may publish revised and/or new versions
of the General Public License from time to time.  Such new versions will
be similar in spirit to the present version, but may differ in detail to
address new problems or concerns.

Each version is given a distinguishing version number.  If the Program
specifies a version number of this License which applies to it and "any
later version", you have the option of following the terms and conditions
either of that version or of any later version published by the Free
Software Foundation.  If the Program does not specify a version number of
this License, you may choose any version ever published by the Free Software
Foundation.

  10. If you wish to incorporate parts of the Program into other free
programs whose distribution conditions are different, write to the author
to ask for permission.  For software which is copyrighted by the Free
Software Foundation, write to the Free Software Foundation; we sometimes
make exceptions for this.  Our decision will be guided by the two goals
of preserving the free status of all derivatives of our free software and
of promoting the sharing and reuse of software generally.

                            NO WARRANTY

  11. BECAUSE THE PROGRAM IS LICENSED FREE OF CHARGE, THERE IS NO WARRANTY
FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW.  EXCEPT WHEN
OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES
PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED
OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE.  THE ENTIRE RISK AS
TO THE QUALITY AND PERFORMANCE OF THE PROGRAM IS WITH YOU.  SHOULD THE
PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL NECESSARY SERVICING,
REPAIR OR CORRECTION.

  12. IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MAY MODIFY AND/OR
REDISTRIBUTE THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES,
INCLUDING ANY GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING
OUT OF THE USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED
TO LOSS OF DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY
YOU OR THIRD PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER
PROGRAMS), EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE
POSSIBILITY OF SUCH DAMAGES.

                     END OF TERMS AND CONDITIONS

            How to Apply These Terms to Your New Programs

  If you develop a new program, and you want it to be of the greatest
possible use to the public, the best way to achieve this is to make it
free software which everyone can redistribute and change under these terms.

  To do so, attach the following notices to the program.  It is safest
to attach them to the start of each source file to most effectively
convey the exclusion of warranty; and each file should have at least
the "copyright" line and a pointer to where the full notice is found.

    <one line to give the program's name and a brief idea of what it does.>
    Copyright (C) <year>  <name of author>

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

Also add information on how to contact you by electronic and paper mail.

If the program is interactive, make it output a short notice like this
when it starts in an interactive mode:

    Gnomovision version 69, Copyright (C) year name of author
    Gnomovision comes with ABSOLUTELY NO WARRANTY; for details type `show w'.
    This is free software, and you are welcome to redistribute it
    under certain conditions; type `show c' for details.

The hypothetical commands `show w' and `show c' should show the appropriate
parts of the General Public License.  Of course, the commands you use may
be called something other than `show w' and `show c'; they could even be
mouse-clicks or menu items--whatever suits your program.

You should also get your employer (if you work as a programmer) or your
school, if any, to sign a "copyright disclaimer" for the program, if
necessary.  Here is a sample; alter the names:

  Yoyodyne, Inc., hereby disclaims all copyright interest in the program
  `Gnomovision' (which makes passes at compilers) written by James Hacker.

  <signature of Ty Coon>, 1 April 1989
  Ty Coon, President of Vice

This General Public License does not permit incorporating your program into
proprietary programs.  If your program is a subroutine library, you may
consider it more useful to permit linking proprietary applications with the
library.  If this is what you want to do, use the GNU Lesser General
Public License instead of this License.
```

### zlib License

```text
Copyright notice:

 (C) 1995-2026 Jean-loup Gailly and Mark Adler

  This software is provided 'as-is', without any express or implied
  warranty.  In no event will the authors be held liable for any damages
  arising from the use of this software.

  Permission is granted to anyone to use this software for any purpose,
  including commercial applications, and to alter it and redistribute it
  freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must not
     claim that you wrote the original software. If you use this software
     in a product, an acknowledgment in the product documentation would be
     appreciated but is not required.
  2. Altered source versions must be plainly marked as such, and must not be
     misrepresented as being the original software.
  3. This notice may not be removed or altered from any source distribution.

  Jean-loup Gailly        Mark Adler
  jloup@gzip.org          madler@alumni.caltech.edu
```

## Full production dependency inventory

### @esbuild/win32-x64 0.28.1

License: MIT

### @jridgewell/gen-mapping 0.3.13

License: MIT

### @jridgewell/resolve-uri 3.1.2

License: MIT

### @jridgewell/source-map 0.3.11

License: MIT

### @jridgewell/sourcemap-codec 1.5.5

License: MIT

### @jridgewell/trace-mapping 0.3.31

License: MIT

### @mediabunny/aac-encoder 1.50.8

License: MPL-2.0

### @mediabunny/flac-encoder 1.50.8

License: MPL-2.0

### @mediabunny/mp3-encoder 1.50.8

License: MPL-2.0

### @module-federation/error-codes 0.22.0

License: MIT

### @module-federation/runtime 0.22.0

License: MIT

### @module-federation/runtime-core 0.22.0

License: MIT

### @module-federation/runtime-tools 0.22.0

License: MIT

### @module-federation/sdk 0.22.0

License: MIT

### @module-federation/webpack-bundler-runtime 0.22.0

License: MIT

### @oxc-project/types 0.146.0

License: MIT

### @remotion/bundler 4.0.507

License: Remotion License (see verbatim text above)

### @remotion/captions 4.0.507

License: MIT (see Remotion MIT notice above)

### @remotion/compositor-win32-x64-msvc 4.0.507

License: Remotion License (see verbatim text above)

### @remotion/licensing 4.0.507

License: MIT (see Remotion MIT notice above)

### @remotion/media-parser 4.0.507

License: Remotion License (see verbatim text above)

### @remotion/media-utils 4.0.507

License: MIT (see Remotion MIT notice above)

### @remotion/player 4.0.507

License: Remotion License (see verbatim text above)

### @remotion/renderer 4.0.507

License: Remotion License (see verbatim text above)

### @remotion/streaming 4.0.507

License: MIT (see Remotion MIT notice above)

### @remotion/studio 4.0.507

License: MIT (see Remotion MIT notice above)

### @remotion/studio-protocol 4.0.507

License: Remotion License (see verbatim text above)

### @remotion/studio-shared 4.0.507

License: MIT (see Remotion MIT notice above)

### @remotion/timeline-utils 4.0.507

License: MIT (see Remotion MIT notice above)

### @remotion/web-renderer 4.0.507

License: Remotion License (see verbatim text above)

### @remotion/zod-types 4.0.507

License: MIT (see Remotion MIT notice above)

### @rolldown/binding-win32-x64-msvc 1.2.5

License: MIT

### @rolldown/pluginutils 1.0.1

License: MIT

### @rspack/binding 1.7.11

License: MIT

### @rspack/binding-win32-x64-msvc 1.7.11

License: MIT

### @rspack/core 1.7.11

License: MIT

### @rspack/lite-tapable 1.1.0

License: MIT

### @rspack/plugin-react-refresh 1.6.1

License: MIT

### @types/dom-mediacapture-transform 0.1.12

License: MIT

### @types/dom-webcodecs 0.1.13

License: MIT

### @types/eslint 9.6.1

License: MIT

### @types/eslint-scope 3.7.7

License: MIT

### @types/estree 1.0.9

License: MIT

### @types/json-schema 7.0.15

License: MIT

### @types/node 26.2.0

License: MIT

### @vitejs/plugin-react 6.1.0

License: MIT

### @webassemblyjs/ast 1.14.1

License: MIT

### @webassemblyjs/floating-point-hex-parser 1.13.2

License: MIT

### @webassemblyjs/helper-api-error 1.13.2

License: MIT

### @webassemblyjs/helper-buffer 1.14.1

License: MIT

### @webassemblyjs/helper-numbers 1.13.2

License: MIT

### @webassemblyjs/helper-wasm-bytecode 1.13.2

License: MIT

### @webassemblyjs/helper-wasm-section 1.14.1

License: MIT

### @webassemblyjs/ieee754 1.13.2

License: MIT

### @webassemblyjs/leb128 1.13.2

License: Apache-2.0

### @webassemblyjs/utf8 1.13.2

License: MIT

### @webassemblyjs/wasm-edit 1.14.1

License: MIT

### @webassemblyjs/wasm-gen 1.14.1

License: MIT

### @webassemblyjs/wasm-opt 1.14.1

License: MIT

### @webassemblyjs/wasm-parser 1.14.1

License: MIT

### @webassemblyjs/wast-printer 1.14.1

License: MIT

### @xtuc/ieee754 1.2.0

License: BSD-3-Clause

### @xtuc/long 4.2.2

License: Apache-2.0

### acorn 8.18.0

License: MIT

### acorn-import-phases 1.0.4

License: MIT

### adm-zip 0.5.18

License: MIT

### ajv 8.20.0

License: MIT

### ajv-formats 2.1.1

License: MIT

### ajv-keywords 5.1.0

License: MIT

### baseline-browser-mapping 2.11.13

License: Apache-2.0

### browserslist 4.28.8

License: MIT

### buffer-from 1.1.2

License: MIT

### caniuse-lite 1.0.30001809

License: CC-BY-4.0

### chrome-trace-event 1.0.4

License: MIT

### commander 2.20.3

License: MIT

### cross-spawn 7.0.6

License: MIT

### css-loader 7.1.4

License: MIT

### cssesc 3.0.0

License: MIT

### define-lazy-prop 2.0.0

License: MIT

### detect-libc 2.1.2

License: Apache-2.0

### electron-to-chromium 1.5.403

License: ISC

### enhanced-resolve 5.24.5

License: MIT

### error-stack-parser 2.1.4

License: MIT

### es-module-lexer 2.3.1

License: MIT

### esbuild 0.28.1

License: MIT

### escalade 3.2.0

License: MIT

### eslint-scope 5.1.1

License: BSD-2-Clause

### esrecurse 4.3.0

License: BSD-2-Clause

### estraverse 4.3.0, 5.3.0

License: BSD-2-Clause

### events 3.3.0

License: MIT

### execa 5.1.1

License: MIT

### fast-deep-equal 3.1.3

License: MIT

### fast-uri 3.1.5

License: BSD-3-Clause

### fdir 6.5.0

License: MIT

### framer-motion 13.0.0

License: MIT

### fs-monkey 1.0.3

License: Unlicense

### get-stream 6.0.1

License: MIT

### glob-to-regexp 0.4.1

License: BSD-2-Clause

### graceful-fs 4.2.11

License: ISC

### has-flag 4.0.0

License: MIT

### html-entities 2.6.0

License: MIT

### html-to-image 1.11.13

License: MIT

### human-signals 2.1.0

License: Apache-2.0

### icss-utils 5.1.0

License: ISC

### is-docker 2.2.1

License: MIT

### is-stream 2.0.1

License: MIT

### is-wsl 2.2.0

License: MIT

### isexe 2.0.0

License: ISC

### jest-worker 27.5.1

License: MIT

### jiti 2.7.0

License: MIT

### json-parse-even-better-errors 2.3.1

License: MIT

### json-schema-traverse 1.0.0

License: MIT

### lightningcss 1.33.0

License: MPL-2.0

### lightningcss-win32-x64-msvc 1.33.0

License: MPL-2.0

### loader-runner 4.3.2

License: MIT

### lru-cache 6.0.0

License: ISC

### mediabunny 1.50.8

License: MPL-2.0

### memfs 3.4.3

License: Unlicense

### merge-stream 2.0.0

License: MIT

### mime-db 1.52.0

License: MIT

### mime-types 2.1.35

License: MIT

### mimic-fn 2.1.0

License: MIT

### motion 13.0.0

License: MIT

### motion-dom 13.0.0

License: MIT

### motion-utils 13.0.0

License: MIT

### nanoid 3.3.18

License: MIT

### neo-async 2.6.2

License: MIT

### node-releases 2.0.53

License: MIT

### npm-run-path 4.0.1

License: MIT

### onetime 5.1.2

License: MIT

### open 8.4.2

License: MIT

### path-key 3.1.1

License: MIT

### picocolors 1.1.1

License: ISC

### picomatch 4.0.5

License: MIT

### postcss 8.5.26

License: MIT

### postcss-modules-extract-imports 3.1.0

License: ISC

### postcss-modules-local-by-default 4.2.0

License: MIT

### postcss-modules-scope 3.2.1

License: ISC

### postcss-modules-values 4.0.0

License: ISC

### postcss-selector-parser 7.1.5

License: MIT

### postcss-value-parser 4.2.0

License: MIT

### react 19.2.8

License: MIT

### react-dom 19.2.8

License: MIT

### react-refresh 0.18.0

License: MIT

### remotion 4.0.507

License: Remotion License (see verbatim text above)

### require-from-string 2.0.2

License: MIT

### rolldown 1.2.5

License: MIT

### scheduler 0.27.0

License: MIT

### schema-utils 4.3.3

License: MIT

### semver 7.5.3, 7.8.5

License: ISC

### shebang-command 2.0.0

License: MIT

### shebang-regex 3.0.0

License: MIT

### signal-exit 3.0.7

License: ISC

### source-map 0.6.1, 0.8.0

License: BSD-3-Clause

### source-map-js 1.2.1

License: BSD-3-Clause

### source-map-support 0.5.21

License: MIT

### stackframe 1.3.4

License: MIT

### strip-final-newline 2.0.0

License: MIT

### style-loader 4.0.0

License: MIT

### supports-color 8.1.1

License: MIT

### tapable 2.3.3

License: MIT

### terser 5.49.2

License: BSD-2-Clause

### terser-webpack-plugin 5.6.1

License: MIT

### tinyglobby 0.2.17

License: MIT

### tslib 2.8.1

License: 0BSD

### typescript 5.9.3

License: Apache-2.0

### undici-types 8.3.0

License: MIT

### update-browserslist-db 1.3.0

License: MIT

### util-deprecate 1.0.2

License: MIT

### vite 8.2.2

License: MIT

### watchpack 2.5.2

License: MIT

### webpack 5.105.0

License: MIT

### webpack-sources 3.5.1

License: MIT

### which 2.0.2

License: ISC

### ws 8.21.0

License: MIT

### yallist 4.0.0

License: ISC

### zod 4.4.3

License: MIT
