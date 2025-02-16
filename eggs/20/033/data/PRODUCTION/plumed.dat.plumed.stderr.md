**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[fv-az1939-440:65817] *** Process received signal ***
[fv-az1939-440:65817] Signal: Aborted (6)
[fv-az1939-440:65817] Signal code:  (-6)
[fv-az1939-440:65817] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3828645330]
[fv-az1939-440:65817] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f382869eb2c]
[fv-az1939-440:65817] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f382864527e]
[fv-az1939-440:65817] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f38286288ff]
[fv-az1939-440:65817] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3828aa5ff5]
[fv-az1939-440:65817] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3828abb0da]
[fv-az1939-440:65817] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3828aa5a55]
[fv-az1939-440:65817] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3828aa5a6f]
[fv-az1939-440:65817] [ 8] plumed(+0x146dd)[0x564d21f1c6dd]
[fv-az1939-440:65817] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f382862a1ca]
[fv-az1939-440:65817] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f382862a28b]
[fv-az1939-440:65817] [11] plumed(+0x15365)[0x564d21f1d365]
[fv-az1939-440:65817] *** End of error message ***
</pre>
{% endraw %}
