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
[fv-az1693-957:66636] *** Process received signal ***
[fv-az1693-957:66636] Signal: Aborted (6)
[fv-az1693-957:66636] Signal code:  (-6)
[fv-az1693-957:66636] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f181f245330]
[fv-az1693-957:66636] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f181f29eb2c]
[fv-az1693-957:66636] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f181f24527e]
[fv-az1693-957:66636] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f181f2288ff]
[fv-az1693-957:66636] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f181f6a5ff5]
[fv-az1693-957:66636] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f181f6bb0da]
[fv-az1693-957:66636] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f181f6a5a55]
[fv-az1693-957:66636] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f181f6a5a6f]
[fv-az1693-957:66636] [ 8] plumed(+0x146dd)[0x55de318156dd]
[fv-az1693-957:66636] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f181f22a1ca]
[fv-az1693-957:66636] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f181f22a28b]
[fv-az1693-957:66636] [11] plumed(+0x15365)[0x55de31816365]
[fv-az1693-957:66636] *** End of error message ***
</pre>
{% endraw %}
