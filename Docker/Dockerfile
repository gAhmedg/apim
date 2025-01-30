# Use the WSO2 API Manager image as the base
FROM wso2/wso2am:4.4.0

# Set the working directory in the container
WORKDIR /home/wso2carbon

# Copy the PostgreSQL JDBC driver into the appropriate directory
COPY postgresql-42.7.4.jar /home/wso2carbon/wso2am-4.4.0/repository/components/lib/postgresql-42.7.4.jar

# Copy the MySQL JDBC driver into the appropriate directory
COPY mysql-connector-j-8.0.31.jar /home/wso2carbon/wso2am-4.4.0/repository/components/lib/mysql-connector-j-8.0.31.jar

# No need to redefine the ENTRYPOINT unless you want to customize it
