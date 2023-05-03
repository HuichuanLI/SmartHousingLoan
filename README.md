# SmartHousingLoan

# SmartHousingLoan

一个计算最优化房贷的小项目

# Description

通过输入你的房贷期限、房贷金额、贷款利率、你目前持有的现金、你每月的固定收入、你的理财利率来计算最优的房贷计划

# Input

* 贷款年限(单位:年)
  loan_years
* 贷款金额(单位:万元)
  loan
* 交完首付后持有的现金(单位:万元)
  cash
* 理财年利率
  financial_yearly_return_rate
* 贷款年利率
  lending_yearly_rate
* 每月净收入(扣除生活开销，但不要扣除房贷)(单位:万元)
  monthly_income

# Output

* 每月应还贷款(单位:万元)
  Monthly repayment:    0.1444 * 10000 RMB
* X年后，你手中持有的现金(单位:万元)
  30 years later, your cash:    179.54 * 10000 RMB

# Example

        输入
        房产价格
        property_price = 600
        房产每年的升值
        property_yearly_return_rate = 0.03
        每年贷款利率
        mortgage_yearly_rate = 0.0495
        贷款年限
        mortgage_years = 30
        首付价格
        down_payment = 300
        现金资产
        current_wealth = 300
        每个月工资
        monthly_income = 3
        家庭花费
        family_expense = 0.5
        购票等其他的收入
        financial_yearly_return_rate = 0.03

        输出
       Monthly Mortgage repayment:	 1.6013 * 10000 RMB
       30 years later, your cash wealth:	 572.84 * 10000 RMB
       30 years later, your property wealth:	 1456.36 * 10000 RMB


        每月应还贷款  1.6013 万元
        30年后，你的现金财富将是572.84万元
        30年后，你的总财富将是1456.36 * 10000万元

