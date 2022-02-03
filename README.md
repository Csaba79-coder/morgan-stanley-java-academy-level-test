# Morgan Stanley Java Academy Entrance Exam

## Getting Started

- Create a new **private** repository under your own account
- Grant admin access to the `szelpe` GitHub user
- Create a `.gitignore` file so generated files won't be committed
- Commit your progress frequently and with descriptive commit messages
- All your answers and solutions should go in this repository

## Keep in mind

- You can use any resource online, but **please work individually**
- **Don't just copy-paste** your answers and solutions, use your own words
  instead
  
## Task
  
### Fish tank

Now you are going to create a simple aquarium
where you can take care of your fishes.

#### Fish

Each fish has a name, weight and a color.

- The fish has a `status()` method. It should print the status for a fish.

  - For example: `Dory, weight: 9, color: blue, short-term memory loss: true`

- The fish has a `feed()` method. The implementation should depend
  on the type of the fish.

##### Clownfish

Clownfish, gains 1 gramm when fed and
has an additional color (color of the stripes).

##### Tang

Tang, gains 1 gramm when fed and can suffer short-term memory loss.

##### Kong

Kong, gains 2 grams when fed.

#### Aquarium

- It has an `addFish()` method where you can add fishes to the aquarium.

- It has a `feed()` method that feeds all the fishes in the aquarium:

  - Increases the weight of every fish with the amount of grams
    they gain when fed.

- It has a `removeFish()` a method that removes the big fishes: 

  - A big fish's weight is at least 11 grams.

- The aquarium has a `getStatus()` method it should print
  the status for each fish.
