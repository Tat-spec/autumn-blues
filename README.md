# autumn-bluesclass AutumnBlues:
    def __init__(self, season, weather):
        self.season = season  # Current season
        self.weather = weather  # Weather condition (e.g., cloudy, rainy, sunny)
    
    def check_mood(self):
        if self.season.lower() == "autumn":
            if self.weather.lower() in ["cloudy", "rainy"]:
                print("Feeling the autumn blues... Time for a cozy blanket and hot tea.")
            elif self.weather.lower() == "sunny":
                print("A bright autumn day! Feeling nostalgic but cheerful.")
            else:
                print("A calm autumn day, with a mix of melancholy and peace.")
        else:
            print("Not autumn, feeling neutral or upbeat!")

# Example usage:
mood = AutumnBlues(season="Autumn", weather="Rainy")
mood.check_mood()
