**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=distcv FUNCTION=cv
Maybe a missing space or a typo?
[fv-az985-228:69847] *** Process received signal ***
[fv-az985-228:69847] Signal: Aborted (6)
[fv-az985-228:69847] Signal code:  (-6)
[fv-az985-228:69847] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5bf5442520]
[fv-az985-228:69847] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5bf54969fc]
[fv-az985-228:69847] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5bf5442476]
[fv-az985-228:69847] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5bf54287f3]
[fv-az985-228:69847] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f5bf58a4f26]
[fv-az985-228:69847] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f5bf58b6d9c]
[fv-az985-228:69847] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f5bf58b6e07]
[fv-az985-228:69847] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5bf58b70bb]
[fv-az985-228:69847] [ 8] plumed(+0x12f48)[0x558abbc28f48]
[fv-az985-228:69847] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5bf5429d90]
[fv-az985-228:69847] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5bf5429e40]
[fv-az985-228:69847] [11] plumed(+0x131e5)[0x558abbc291e5]
[fv-az985-228:69847] *** End of error message ***
</pre>
{% endraw %}
