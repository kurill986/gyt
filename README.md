
using namespace std;

int main() {

            srand(time(0));

            int sum;

            for (int i = 0; i < 1000; i++) {

                                       sum = rand() % 6 + 1 + rand() % 6 + 1; 
                                       cout << sum << " ";

                                       if ((i + 1) % 10 == 0) cout << endl;

            }

}#   n u t  
 