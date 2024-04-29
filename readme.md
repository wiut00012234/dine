# DineIn Project

## Overview

Welcome to the DineIn project! DineIn is a modern solution designed to revolutionize the dining experience. Our platform connects food enthusiasts with local restaurants, allowing users to book tables, order food online, and even customize their dining experiences according to their dietary preferences.

## Features

-   **Table Reservation**: Book your table in advance from your favorite restaurants.
-   **Online Ordering**: Browse menus and place orders directly from the app.
-   **Dietary Customization**: Filter menu items based on dietary needs and preferences.
-   **Ratings and Reviews**: Share your experience and read reviews from others.
-   **Loyalty Program**: Earn points with every order and redeem them for discounts.

## Getting Started

### Prerequisites

-   Docker
-   PHP >= 7.4
-   Composer
-   Node.js and npm

### Installation

1. Clone the repository:

```
git clone https://github.com/wiut00012234/dinein.git
```

2. Navigate to the project directory:

```
cd dinein
```

3. Install PHP dependencies:

```
composer install
```

4. Install JavaScript dependencies:

```
npm install
```

5. Copy the example env file and make the necessary configuration adjustments:

```
cp .env.example .env
```

6. Generate an app encryption key:

```
php artisan key:generate
```

7. Run the application using Laravel Sail (Docker):

```
./vendor/bin/sail up
```

## Usage

After installation, DineIn can be accessed at `http://localhost`.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
