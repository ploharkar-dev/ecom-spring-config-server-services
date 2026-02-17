# FUllSTOP Config Server

Spring Cloud Config Server for centralized configuration management of the FUllSTOP e-commerce platform.

## Overview

This is a Spring Cloud Config Server that manages configurations for:
- Development environment
- Testing environment  
- Production environment

The server reads configuration from the ConfigRepo (Git repository) and serves them to client applications.

## Quick Start

### 1. Build the Project

```bash
cd SpringConfigServer
mvn clean install
```

### 2. Run the Config Server