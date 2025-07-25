**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmpptgkbjq6m:10673] *** Process received signal ***
[pkrvmpptgkbjq6m:10673] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10673] Signal code:  (-6)
[pkrvmpptgkbjq6m:10673] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f043d045330]
[pkrvmpptgkbjq6m:10673] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f043d09eb2c]
[pkrvmpptgkbjq6m:10673] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f043d04527e]
[pkrvmpptgkbjq6m:10673] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f043d0288ff]
[pkrvmpptgkbjq6m:10673] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f043d4a5ff5]
[pkrvmpptgkbjq6m:10673] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f043d4bb0da]
[pkrvmpptgkbjq6m:10673] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f043d4a5a55]
[pkrvmpptgkbjq6m:10673] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f043d4a5a6f]
[pkrvmpptgkbjq6m:10673] [ 8] plumed(+0x146dd)[0x5581d55da6dd]
[pkrvmpptgkbjq6m:10673] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f043d02a1ca]
[pkrvmpptgkbjq6m:10673] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f043d02a28b]
[pkrvmpptgkbjq6m:10673] [11] plumed(+0x15365)[0x5581d55db365]
[pkrvmpptgkbjq6m:10673] *** End of error message ***
</pre>
{% endraw %}
