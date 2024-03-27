**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-2-jax/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,3,4 IMPORT=distcv FUNCTION=cv COMPONENTS=d12,d13
Maybe a missing space or a typo?
[fv-az985-228:70097] *** Process received signal ***
[fv-az985-228:70097] Signal: Aborted (6)
[fv-az985-228:70097] Signal code:  (-6)
[fv-az985-228:70097] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd631442520]
[fv-az985-228:70097] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd6314969fc]
[fv-az985-228:70097] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd631442476]
[fv-az985-228:70097] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd6314287f3]
[fv-az985-228:70097] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd6318a4f26]
[fv-az985-228:70097] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd6318b6d9c]
[fv-az985-228:70097] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd6318b6e07]
[fv-az985-228:70097] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd6318b70bb]
[fv-az985-228:70097] [ 8] plumed(+0x12f48)[0x56023e98ef48]
[fv-az985-228:70097] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd631429d90]
[fv-az985-228:70097] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd631429e40]
[fv-az985-228:70097] [11] plumed(+0x131e5)[0x56023e98f1e5]
[fv-az985-228:70097] *** End of error message ***
</pre>
{% endraw %}
