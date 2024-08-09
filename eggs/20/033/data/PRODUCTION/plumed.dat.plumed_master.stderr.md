**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[fv-az768-943:08806] *** Process received signal ***
[fv-az768-943:08806] Signal: Aborted (6)
[fv-az768-943:08806] Signal code:  (-6)
[fv-az768-943:08806] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f185fe42520]
[fv-az768-943:08806] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f185fe969fc]
[fv-az768-943:08806] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f185fe42476]
[fv-az768-943:08806] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f185fe287f3]
[fv-az768-943:08806] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f18602a2b9e]
[fv-az768-943:08806] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f18602ae20c]
[fv-az768-943:08806] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f18602ae277]
[fv-az768-943:08806] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f18602ae52b]
[fv-az768-943:08806] [ 8] plumed_master(+0x14274)[0x55a316ff5274]
[fv-az768-943:08806] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f185fe29d90]
[fv-az768-943:08806] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f185fe29e40]
[fv-az768-943:08806] [11] plumed_master(+0x14ed5)[0x55a316ff5ed5]
[fv-az768-943:08806] *** End of error message ***
</pre>
{% endraw %}
