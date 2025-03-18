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
[fv-az1950-95:64004] *** Process received signal ***
[fv-az1950-95:64004] Signal: Aborted (6)
[fv-az1950-95:64004] Signal code:  (-6)
[fv-az1950-95:64004] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f699e045330]
[fv-az1950-95:64004] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f699e09eb2c]
[fv-az1950-95:64004] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f699e04527e]
[fv-az1950-95:64004] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f699e0288ff]
[fv-az1950-95:64004] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f699e4a5ff5]
[fv-az1950-95:64004] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f699e4bb0da]
[fv-az1950-95:64004] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f699e4a5a55]
[fv-az1950-95:64004] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f699e4a5a6f]
[fv-az1950-95:64004] [ 8] plumed(+0x146dd)[0x55d3d099e6dd]
[fv-az1950-95:64004] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f699e02a1ca]
[fv-az1950-95:64004] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f699e02a28b]
[fv-az1950-95:64004] [11] plumed(+0x15365)[0x55d3d099f365]
[fv-az1950-95:64004] *** End of error message ***
</pre>
{% endraw %}
