cryptol.vim
===========

Copyright © 2013 Edward O'Callaghan. All Rights Reserved.

A ViM plugin functionality for the Cryptol programming language.
<pre>

  .oooooo.                                       .             oooo  
 d8P'  `Y8b                                    .o8             `888  
888          oooo d8b oooo    ooo oo.ooooo.  .o888oo  .ooooo.   888  
888          `888""8P  `88.  .8'   888' `88b   888   d88' `88b  888  
888           888       `88..8'    888   888   888   888   888  888  
`88b    ooo   888        `888'     888   888   888 . 888   888  888  
 `Y8bood8P'  d888b        .8'      888bod8P'   "888" `Y8bod8P' o888o 
                      .o..P'       888                               
                      `Y8P'       o888o                              

        Functionality for the Cryptol programming language.
        Includes syntax highlighting, code folding, and more!

==============================================================================
CONTENTS                                                      *CryptolContents*

    1. Usage ................ |CryptolUsage|
    2. Mappings ............. |CryptolMappings|
    3. License .............. |CryptolLicense|
    4. Bugs ................. |CryptolBugs|
    5. Contributing ......... |CryptolContributing|
    6. Changelog ............ |CryptolChangelog|
    7. Credits .............. |CryptolCredits|

==============================================================================
Section 1: Usage                                                 *CryptolUsage*

This plugin will automatically provide syntax highlighting for Cryptol files
(files ending in .cry).

Cryptol is a purely functional domain specific language, developed over the
past decade by Galois for the NSA, for the design, implementation and
verification of cryptographic algorithms.

==============================================================================
Section 2: Mappings                                           *CryptolMappings*

==============================================================================
Section 3: License                                             *CryptolLicense*

Copyright © 2013 Edward O'Callaghan. All Rights Reserved.

HOWEVER:
Be it known, The syntax file was written by
Copyright © 2005 Fergus Henderson. All Rights Reserved.


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

==============================================================================
Section 4: Bugs                                                   *CryptolBugs*

 * https://github.com/victoredwardocallaghan/cryptol.vim/issues

==============================================================================
Section 5: Contributing                                   *CryptolContributing*

 * Edward O'Callaghan
 * Hugo Vincent

==============================================================================
Section 6: Changelog                                         *CryptolChangelog*

 * 23 Aug 2021 - Fix highlighting of number literals, 1_000_000
 * 23 Aug 2021 - Fix `property` keyword missed highlighting
 * 23 Aug 2021 - Fix :command -nargs usage
 * 09 May 2016 - Add highlighting of FIXME, TODO and XXX.
 * 05 May 2016 - Add module keywords for Cryptol 2, fix bug in number
 				 syntax highlighting.
 * 25 Apr 2013 - Add initial compiler support - WIP.
 * 25 Apr 2013 - Initial.

==============================================================================
Section 7: Credits                                             *CryptolCredits*

 * Edward O'Callaghan
 * Fergus Henderson
 * Max Ulidtko

</pre>
