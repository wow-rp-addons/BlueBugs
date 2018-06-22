BlueBugs UI Fixes
=================
This is a small collection of fixes for World of Warcraft UI/taint issues,
primarily those stemming from Blizzard UI bugs or oversights that cause official
APIs used in documented ways to spread taint through the UI.

The two fixes currently contained are:

* UIDropDownMenu value tainting
* InterfaceCategoryList selection tainting

More information on these fixes and possible ways Blizzard employees may be able
to fix them on the other side (hint, hint!), please see the comments in the Lua
source files.

Including These Fixes in Your AddOn
===================================
Embedding these UI fixes in your addon is supported.

To include these fixes, please add an entry for "BlueBugs\BlueBugs.xml" (note
the file extension) to your addon's .toc file, with the proper extra path for
where your addon keeps copies of libraries. Doing this guarantees all UI fixes
will be loaded properly in any future version, regardless of whether new fixes
are added or old fixes are removed.

Copyright and Permissions Notices
=================================
Copyright and permission notices are included in the headers of all substantial
files. Files without copyright or permission notices are considered by the
author to not meet the theshold of originality required for copyright, thus
consisting solely of non-copyrightable material, and may be treated as such.

The year is *not* necessarily included in these copyright notices, as it is not
required under the Berne Convention, and makes little sense for an author
clearly identified by their legal name in a country where copyright term for an
individual-authored work is limited based on the author's life. In the event of
an author's death, the notices will be updated to reflect the year of death for
that individual, assuming anyone is capable of doing so. Otherwise, obituaries
and official records will need to be relied upon in the distant future.

In the cases of anonymous or pseudonymous contributions that cannot be tied to
a legal name or a lifespan, the year of the contribution will be included in the
notices for that particular author.

Meaning of the License
======================
In the unlikely case of a legal dispute involving this software, the following
may be used by the courts to judge the original author's intent behind the use
of this license and their understanding of what rights and restrictions it
places on the software.

The author intends the license to permit nearly-unlimited use, modification, and
distribution of the software. The author intends the license to grant the same
permissions and restrictions to modified copies of the software as are granted
to unmodified copies. Authors of modifications may grant additional permissions
or impose additional restrictions on their portions of a modified copy of the
software (potentially adding restrictions on a modified copy of the software as
a whole), but the original author's grants remain the same regardless.

And there's no warranty, interpreted by the original author as meaning nobody
will attempt to sue them over it. The world has been warned that the sofware
could do horrible, unexpected things, and it's not the author's fault.
