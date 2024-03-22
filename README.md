i) read -p "Enter employee name:" employee_name

read -p "Enter hours worked "hours_worked

read -p "Enter rate per hour. "rate_per_hour

ii)basic_pay=$((hours_worked rate_per_hour))

iii) if [ $basic_pay -gt 70000], then tax=25

elif [ $basic_pay ge 15000] && [ Sbasic_pay-le 70000 ]; then tax=15

else

tax=0

fi

tax_amount=$(((basic_pay tax) / 100))

iv) net_pay=$((basic_paytax_amount))

echo "Employee Name. Semployee_name"

echo "Hours Worked Shours_worked"

echo "Rate Per Hour Srate_per_hour"

echo "Basic Pay: Sbasic_pay"

echo "Tax Rate Stax%"

echo "Tax Amount $tax_amount"

echo "Net Pay: $net_pay"
2.#include <stdio.h>

#include <stdlib.h>

#include <fcntl.h>

#include <unistd.h>

int main() {

int fd; char buffer[20];

fd = open("example.txt", O_RDWR | O_CREAT, 0644); if (fd == -1)

{

perror("open");

exit(1);

}
3.i)read -p "Enter CustomerID: " customer_id

read -p "Enter CustomerName: " customer_name

read -p "Enter UnitConsumed: "unit_consumed

ii) if [ $unit_consumed -It 200 ]; then charge_per_unit=120

elif [ $unit_consumed -ge 200 ] && [ $unit_consumed -It 400 ]; then charge_per_unit=150

elif [ $unit_consumed -ge 400 ] && [ $unit_consumed -lt 600 ]; then charge_per_unit=180

else

charge_per_unit=200

fi

iv)echo "CustomerID: Scustomer_id

I

"echo "CustomerName Scustomer_name

"echo "UnitConsumed Sunit_consumed

"echo "Charge per unit Ksh Scharge_per_unit

"echo "Total Bill: Ksh total_bill"
