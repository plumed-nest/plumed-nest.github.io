**Project ID:** [plumID:21.047]({{ '/' | absolute_url }}eggs/21/047/)  
Stderr for source:  Sodium/300K-MetaD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../PairEntropy.uHcyLA.cpp: In member function ‘virtual void PLMD::colvar::PairEntropy::calculate()’:
../../PairEntropy.uHcyLA.cpp:264:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
264 |          if (minBin > (nhist-1)) minBin=nhist-1;
|              ~~~~~~~^~~~~~~~~~~
../../PairEntropy.uHcyLA.cpp:266:21: warning: comparison of integer expressions of different signedness: ‘int’ and ‘unsigned int’ [-Wsign-compare]
266 |          if (maxBin > (nhist-1)) maxBin=nhist-1;
|              ~~~~~~~^~~~~~~~~~~
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PAIRENTROPY LABEL=s2 ATOMS=1-256 MAXR=0.7 SIGMA=0.0125
Maybe a missing space or a typo?
[fv-az1272-890:70949] *** Process received signal ***
[fv-az1272-890:70949] Signal: Aborted (6)
[fv-az1272-890:70949] Signal code:  (-6)
[fv-az1272-890:70949] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f625ca42520]
[fv-az1272-890:70949] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f625ca969fc]
[fv-az1272-890:70949] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f625ca42476]
[fv-az1272-890:70949] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f625ca287f3]
[fv-az1272-890:70949] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f625cea4f26]
[fv-az1272-890:70949] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f625ceb6d9c]
[fv-az1272-890:70949] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f625ceb6e07]
[fv-az1272-890:70949] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f625ceb70bb]
[fv-az1272-890:70949] [ 8] plumed_master(+0x12e7f)[0x55d5693aae7f]
[fv-az1272-890:70949] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f625ca29d90]
[fv-az1272-890:70949] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f625ca29e40]
[fv-az1272-890:70949] [11] plumed_master(+0x13115)[0x55d5693ab115]
[fv-az1272-890:70949] *** End of error message ***
</pre>
{% endraw %}
