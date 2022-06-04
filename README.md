# my-exp

ذخیره تایم استمپ در روابط چند به چند 
public function someRelation()
{
  return $this->belongsToMany('RelatedModel')->withTimestamps();
}
