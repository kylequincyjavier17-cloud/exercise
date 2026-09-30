#exercise
#include <iostream>
using namespace std;

int main() {
    int quarter = 2;

    int start = (quarter - 1) * 3 + 1;
    int end = quarter * 3;

    cout << "Range = " << start << " - " << end << endl;

    return 0;
}
