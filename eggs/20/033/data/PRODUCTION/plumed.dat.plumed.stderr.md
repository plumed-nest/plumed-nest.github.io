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
[fv-az1911-722:08731] *** Process received signal ***
[fv-az1911-722:08731] Signal: Aborted (6)
[fv-az1911-722:08731] Signal code:  (-6)
[fv-az1911-722:08731] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3583a45330]
[fv-az1911-722:08731] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3583a9eb2c]
[fv-az1911-722:08731] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3583a4527e]
[fv-az1911-722:08731] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3583a288ff]
[fv-az1911-722:08731] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3583ea5ff5]
[fv-az1911-722:08731] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3583ebb0da]
[fv-az1911-722:08731] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3583ea5a55]
[fv-az1911-722:08731] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3583ea5a6f]
[fv-az1911-722:08731] [ 8] plumed(+0x146dd)[0x55731275d6dd]
[fv-az1911-722:08731] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3583a2a1ca]
[fv-az1911-722:08731] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3583a2a28b]
[fv-az1911-722:08731] [11] plumed(+0x15365)[0x55731275e365]
[fv-az1911-722:08731] *** End of error message ***
</pre>
{% endraw %}
