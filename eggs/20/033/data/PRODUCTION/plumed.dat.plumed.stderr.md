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
[pkrvmxyh4eaekms:10516] *** Process received signal ***
[pkrvmxyh4eaekms:10516] Signal: Aborted (6)
[pkrvmxyh4eaekms:10516] Signal code:  (-6)
[pkrvmxyh4eaekms:10516] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5298645330]
[pkrvmxyh4eaekms:10516] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f529869eb2c]
[pkrvmxyh4eaekms:10516] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f529864527e]
[pkrvmxyh4eaekms:10516] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f52986288ff]
[pkrvmxyh4eaekms:10516] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5298aa5ff5]
[pkrvmxyh4eaekms:10516] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5298abb0da]
[pkrvmxyh4eaekms:10516] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5298aa5a55]
[pkrvmxyh4eaekms:10516] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5298aa5a6f]
[pkrvmxyh4eaekms:10516] [ 8] plumed(+0x146dd)[0x55cbd6ffd6dd]
[pkrvmxyh4eaekms:10516] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f529862a1ca]
[pkrvmxyh4eaekms:10516] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f529862a28b]
[pkrvmxyh4eaekms:10516] [11] plumed(+0x15365)[0x55cbd6ffe365]
[pkrvmxyh4eaekms:10516] *** End of error message ***
</pre>
{% endraw %}
