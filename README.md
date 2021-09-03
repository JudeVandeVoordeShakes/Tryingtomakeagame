#Square_Cataan
# This will be a square grid
# 5 x 5 grid
# Comprised of sand, brick, wood, sheep, wheat, ore
class Tile:
  def __init__(self, robber_status, colors)
    self.robber_status = robber_status
    self.colors = colors
  pass
class Sand(Tile):
  def __init__(self, capacity, robber_availability)
    self.capacity = capacity
    self.robber_availability = robber_availability
  pass
class Resource(Tile):
  def __init__(self, capacity, type) 
    self.capacity = capacity
    self.type = type
  pass
sand_tile = Sand(capacity=3, robber_availability = True)
brick_tile = Resource(capacity=5, brick)
wood_tile = Resource(capacity=5, wood)
sheep_tile = Resource(capacity=5, sheep)
wheat_tile = Resource(capacity=5, wheat)
ore_tile = Resource(capacity=5, ore)
#current problems: This is probably a bad attempt at making tile classes, need a way to pupulate the grid
