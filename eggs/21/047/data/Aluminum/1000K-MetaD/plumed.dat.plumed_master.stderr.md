**Project ID:** [plumID:21.047]({{ '/' | absolute_url }}eggs/21/047/)  
Stderr for source:  Aluminum/1000K-MetaD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../PairEntropy.WnA3lP.cpp: In member function ‘virtual void PLMD::colvar::PairEntropy::calculate()’:
../../PairEntropy.WnA3lP.cpp:264:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
264 |          if (minBin > (nhist-1)) minBin=nhist-1;
|              ~~~~~~~^~~~~~~~~~~
../../PairEntropy.WnA3lP.cpp:266:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
266 |          if (maxBin > (nhist-1)) maxBin=nhist-1;
|              ~~~~~~~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PAIRENTROPY LABEL=s2 ATOMS=1-256 MAXR=0.7 SIGMA=0.0125
Maybe a missing space or a typo?
[fv-az1272-890:70328] *** Process received signal ***
[fv-az1272-890:70328] Signal: Aborted (6)
[fv-az1272-890:70328] Signal code:  (-6)
[fv-az1272-890:70328] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb3c5842520]
[fv-az1272-890:70328] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb3c58969fc]
[fv-az1272-890:70328] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb3c5842476]
[fv-az1272-890:70328] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb3c58287f3]
[fv-az1272-890:70328] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fb3c5ca4f26]
[fv-az1272-890:70328] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fb3c5cb6d9c]
[fv-az1272-890:70328] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fb3c5cb6e07]
[fv-az1272-890:70328] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb3c5cb70bb]
[fv-az1272-890:70328] [ 8] plumed_master(+0x12e7f)[0x5648fea9de7f]
[fv-az1272-890:70328] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb3c5829d90]
[fv-az1272-890:70328] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb3c5829e40]
[fv-az1272-890:70328] [11] plumed_master(+0x13115)[0x5648fea9e115]
[fv-az1272-890:70328] *** End of error message ***
</pre>
{% endraw %}
