**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONCV LABEL=r ATOMS=1,2,3 IMPORT=curvature FUNCTION=r
Maybe a missing space or a typo?
[fv-az985-228:70035] *** Process received signal ***
[fv-az985-228:70035] Signal: Aborted (6)
[fv-az985-228:70035] Signal code:  (-6)
[fv-az985-228:70035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f51d4c42520]
[fv-az985-228:70035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f51d4c969fc]
[fv-az985-228:70035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f51d4c42476]
[fv-az985-228:70035] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f51d4c287f3]
[fv-az985-228:70035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f51d50a4f26]
[fv-az985-228:70035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f51d50b6d9c]
[fv-az985-228:70035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f51d50b6e07]
[fv-az985-228:70035] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f51d50b70bb]
[fv-az985-228:70035] [ 8] plumed(+0x12f48)[0x559a8e71af48]
[fv-az985-228:70035] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f51d4c29d90]
[fv-az985-228:70035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f51d4c29e40]
[fv-az985-228:70035] [11] plumed(+0x131e5)[0x559a8e71b1e5]
[fv-az985-228:70035] *** End of error message ***
</pre>
{% endraw %}
