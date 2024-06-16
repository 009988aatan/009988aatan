import pygame
import time

# Initialize Pygame
pygame.init()

# Set up the tempo (beats per minute)
bpm = 120
beat_duration = 60.0 / bpm  # Calculate duration of each beat in seconds

# Define some basic percussion sounds (you can replace these with Bollywood instrument samples)
kick_sound = pygame.mixer.Sound("kick.wav")
snare_sound = pygame.mixer.Sound("snare.wav")
hihat_sound = pygame.mixer.Sound("hihat.wav")

# Define a basic rhythm pattern (you can create more complex patterns as needed)
# Example: Kick on beats 1 and 3, snare on beat 2, hihat on every beat
rhythm_pattern = [
    (kick_sound, 0),
    (snare_sound, 1),
    (kick_sound, 2),
    (hihat_sound,⬤
