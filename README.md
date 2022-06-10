### For one-click start of various range containers

openrasp 8080/vulns/   https://github.com/baidu/openrasp.git
```cmd
docker run -it --rm -e IASTIP="http://IP" -e TOKEN="3d6bb430bc3" -e ProjectName="openrasp" registry.cn-hangzhou.aliyuncs.com/tscuite/bachang:openrasp-v8
```

webgoat 8087/WebGoat/   https://github.com/WebGoat/WebGoat.git
```cmd
docker run -it --rm -e IASTIP="http://IP" -e TOKEN="3d6bb430bc3" -e ProjectName="webgoat" registry.cn-hangzhou.aliyuncs.com/tscuite/bachang:webgoat-v8
```

benchmark 8443/benchmark/   https://github.com/OWASP-Benchmark/BenchmarkJava.git
```cmd
docker run -it --rm -e IASTIP="http://IP" -e TOKEN="3d6bb430bc3" -e ProjectName="benchmark" registry.cn-hangzhou.aliyuncs.com/tscuite/bachang:benchmark-v8
```

iast-jar 8085/iast6\?name=hello  https://github.com/spring-projects/spring-boot.git
```cmd
docker run -it --rm -e IASTIP="http://IP" -e TOKEN="3d6bb430bc3" -e ProjectName="iast-jar" registry.cn-hangzhou.aliyuncs.com/tscuite/bachang:iast-jar-v8
```

iast-grpc-java 8888 8083/grpc/send?text=1  https://github.com/HXSecurity/dongtai-grpc-range.git
```cmd
docker run -it --rm -e IASTIP="http://IP" -e TOKEN="3d6bb430bc3" -e ProjectName="iast-grpc-java" registry.cn-hangzhou.aliyuncs.com/tscuite/bachang:iast-grpc-java-v8
```