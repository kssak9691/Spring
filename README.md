@SpringBootApplication(scanBasePackages= {"com.cg.payroll"})
@EntityScan(basePackages="com.cg.payroll.beans")
@EnableJpaRepositories(basePackages="com.cg.payroll.daoservices")
@EnableWebMvc
