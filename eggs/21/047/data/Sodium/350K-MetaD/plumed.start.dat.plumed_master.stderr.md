**Project ID:** [plumID:21.047]({{ '/' | absolute_url }}eggs/21/047/)  
Stderr for source:  Sodium/350K-MetaD/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../PairEntropy.eyelaK.cpp: In member function ‘virtual void PLMD::colvar::PairEntropy::calculate()’:
../../PairEntropy.eyelaK.cpp:264:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
264 |          if (minBin > (nhist-1)) minBin=nhist-1;
|              ~~~~~~~^~~~~~~~~~~
../../PairEntropy.eyelaK.cpp:266:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
266 |          if (maxBin > (nhist-1)) maxBin=nhist-1;
|              ~~~~~~~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PAIRENTROPY LABEL=s2 ATOMS=1-256 MAXR=0.7 SIGMA=0.0125
Maybe a missing space or a typo?
[fv-az1272-890:71259] *** Process received signal ***
[fv-az1272-890:71259] Signal: Aborted (6)
[fv-az1272-890:71259] Signal code:  (-6)
[fv-az1272-890:71259] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7b36c42520]
[fv-az1272-890:71259] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7b36c969fc]
[fv-az1272-890:71259] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7b36c42476]
[fv-az1272-890:71259] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7b36c287f3]
[fv-az1272-890:71259] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f7b370a4f26]
[fv-az1272-890:71259] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f7b370b6d9c]
[fv-az1272-890:71259] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f7b370b6e07]
[fv-az1272-890:71259] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7b370b70bb]
[fv-az1272-890:71259] [ 8] plumed_master(+0x12e7f)[0x55586ed12e7f]
[fv-az1272-890:71259] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7b36c29d90]
[fv-az1272-890:71259] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7b36c29e40]
[fv-az1272-890:71259] [11] plumed_master(+0x13115)[0x55586ed13115]
[fv-az1272-890:71259] *** End of error message ***
</pre>
{% endraw %}
