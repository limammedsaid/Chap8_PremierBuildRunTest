# Chap8_PremierBuildRunTest
####### Build ##########
mkdir -p /tmp/xavki/
rm -rf /tmp/xavki/*
echo '
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}

####### Run ##########
cd /tmp/xavki/
java Main >test.file


####### Test ##########
cd /tmp/xavki/
echo "###### contenu du test.file ######"
cat test.file

