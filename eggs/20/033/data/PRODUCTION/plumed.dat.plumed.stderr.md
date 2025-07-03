**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[pkrvmbietmlfzoi:11068] *** Process received signal ***
[pkrvmbietmlfzoi:11068] Signal: Aborted (6)
[pkrvmbietmlfzoi:11068] Signal code:  (-6)
[pkrvmbietmlfzoi:11068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f867ba45330]
[pkrvmbietmlfzoi:11068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f867ba9eb2c]
[pkrvmbietmlfzoi:11068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f867ba4527e]
[pkrvmbietmlfzoi:11068] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f867ba288ff]
[pkrvmbietmlfzoi:11068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f867bea5ff5]
[pkrvmbietmlfzoi:11068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f867bebb0da]
[pkrvmbietmlfzoi:11068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f867bea5a55]
[pkrvmbietmlfzoi:11068] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f867bea5a6f]
[pkrvmbietmlfzoi:11068] [ 8] plumed(+0x146dd)[0x561f14d176dd]
[pkrvmbietmlfzoi:11068] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f867ba2a1ca]
[pkrvmbietmlfzoi:11068] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f867ba2a28b]
[pkrvmbietmlfzoi:11068] [11] plumed(+0x15365)[0x561f14d18365]
[pkrvmbietmlfzoi:11068] *** End of error message ***
</pre>
{% endraw %}
